<script lang="ts">
  // Aquí podrías definir dinámicamente los servicios si quieres que sea más escalable
  const services = [
    {
      title: 'Desarrollo Backend',
      description: 'Diseño y desarrollo de APIs REST y GraphQL con Python/Django y Go. Integraciones con bases de datos, autenticación, seguridad y despliegue en la nube.',
      icon: '/backend.svg'
    },
    {
      title: 'Desarrollo Frontend',
      description: 'Creación de interfaces responsivas y dinámicas con Svelte, React o Angular, optimizadas para rendimiento y experiencia de usuario.',
      icon: '/frontend.svg'
    },
    {
      title: 'Pruebas y Optimización',
      description: 'Pruebas unitarias, de carga y estrés con Pytest y JMeter. Optimización de consultas SQL, control de calidad con SonarQube y CI/CD.',
      icon: '/testing.svg'
    },
    {
      title: 'Despliegue en la Nube',
      description: 'Automatización de despliegues con Docker, despliegue en Google Cloud (Cloud Run, Compute Engine), configuración de servidores Apache y Nginx.',
      icon: '/cloud.svg'
    }
  ]
</script>

<section class="bg-white py-20 px-4 max-w-7xl mx-auto">
  <h1 class="text-4xl font-extrabold mb-8 text-center">Servicios</h1>
  <p class="text-gray-600 mb-12 text-center text-lg max-w-3xl mx-auto">
    Te ofrezco soluciones a la medida para tus proyectos digitales: desde desarrollo backend y frontend hasta despliegue en la nube y optimización de rendimiento.
  </p>

  <div class="grid gap-8 md:grid-cols-2 lg:grid-cols-4">
    {#each services as service}
      <div class="bg-gray-50 p-8 rounded-2xl shadow-lg flex flex-col items-center text-center transition hover:-translate-y-1 hover:shadow-xl">
        <img src={service.icon} alt={service.title} class="h-20 mb-6" />
        <h3 class="text-2xl font-semibold mb-4">{service.title}</h3>
        <p class="text-gray-600 text-base">{service.description}</p>
      </div>
    {/each}
  </div>

  <div class="mt-16 text-center">
    <a href="/contacto" class="inline-block bg-blue-600 hover:bg-blue-700 text-white text-[18px] font-bold px-8 py-4 rounded-full transition">
      Contáctame y trabajemos juntos
    </a>
  </div>
</section>
