<script lang="ts">
  import { onMount } from 'svelte'
  import emailjs from 'emailjs-com'

  let name = '', email = '', subject = '', message = '', loading = false
  const serviceId = import.meta.env.VITE_EMAILJS_SERVICE_ID
  const templateId = import.meta.env.VITE_EMAILJS_TEMPLATE_ID
  const publicKey = import.meta.env.VITE_EMAILJS_PUBLIC_KEY
  const siteKey = import.meta.env.VITE_RECAPTCHA_SITE_KEY

  let recaptchaWidgetId: number | null = null

  // Renderiza el reCAPTCHA cuando se monta el componente
  onMount(() => {
    if (window.grecaptcha) {
      renderRecaptcha()
    } else {
      const interval = setInterval(() => {
        if (window.grecaptcha) {
          clearInterval(interval)
          renderRecaptcha()
        }
      }, 300)
    }
  })

  function renderRecaptcha() {
    const recaptchaContainer = document.querySelector('.g-recaptcha')
    if (recaptchaContainer && !recaptchaWidgetId) {
      recaptchaWidgetId = window.grecaptcha.render(recaptchaContainer as HTMLElement, {
        sitekey: siteKey
      })
    }
  }

  const handleSubmit = async (e: SubmitEvent) => {
    e.preventDefault()

    const recaptchaResponse = window.grecaptcha.getResponse()

    if (!recaptchaResponse) {
      alert('Por favor verifica que no eres un robot.')
      return
    }

    loading = true

    const templateParams = { name, email, subject, message }

    emailjs.send(serviceId, templateId, templateParams, publicKey)
      .then(() => {
        alert('¡Gracias por tu mensaje! Te responderé pronto.')
        name = email = subject = message = ''
        if (recaptchaWidgetId !== null) {
          window.grecaptcha.reset(recaptchaWidgetId)
        }
        loading = false
      })
      .catch(error => {
        console.error(error)
        alert('Ocurrió un error al enviar el mensaje.')
        loading = false
      })
  }
</script>

<section class="bg-white py-20 px-4 max-w-4xl mx-auto">
  <h2 class="text-4xl font-bold mb-8 text-center">Contacto</h2>
  <p class="text-gray-600 mb-12 text-center text-lg">¿Quieres trabajar conmigo o tienes alguna consulta? Escríbeme.</p>

  <form on:submit|preventDefault={handleSubmit} class="space-y-6 bg-gray-50 p-8 rounded-2xl shadow-lg">
    <label class="block">
      <span class="text-gray-700 font-medium">Nombre</span>
      <input type="text" bind:value={name} required class="mt-2 block w-full border border-gray-300 rounded-lg p-3 focus:ring focus:ring-blue-200" />
    </label>

    <label class="block">
      <span class="text-gray-700 font-medium">Correo</span>
      <input type="email" bind:value={email} required class="mt-2 block w-full border border-gray-300 rounded-lg p-3 focus:ring focus:ring-blue-200" />
    </label>

    <label class="block">
      <span class="text-gray-700 font-medium">Asunto</span>
      <input type="text" bind:value={subject} required class="mt-2 block w-full border border-gray-300 rounded-lg p-3 focus:ring focus:ring-blue-200" />
    </label>

    <label class="block">
      <span class="text-gray-700 font-medium">Mensaje</span>
      <textarea bind:value={message} required rows="5" class="mt-2 block w-full border border-gray-300 rounded-lg p-3 focus:ring focus:ring-blue-200"></textarea>
    </label>

    <div class="flex justify-center">
      <div class="g-recaptcha"></div>
    </div>

    <button type="submit" class="w-full bg-blue-600 text-white font-semibold px-6 py-3 rounded-lg hover:bg-blue-700 transition disabled:opacity-50" disabled={loading}>
      {loading ? 'Enviando...' : 'Enviar'}
    </button>
  </form>

  <div class="mt-16 text-center text-gray-600">
    <p>También puedes escribirme directamente a:</p>
    <a href="mailto:nicolassergio6@gmail.com" class="font-medium text-blue-600 hover:underline">nicolassergio6@gmail.com</a>
  </div>
</section>
