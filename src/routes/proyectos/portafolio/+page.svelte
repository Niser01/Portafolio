<div class="relative overflow-hidden">
  <!-- Fondo gradiente -->
  <div class="absolute inset-0 z-0" style="background: linear-gradient(-66deg, #140544 0%, #0F172A 100%);"></div>

  <!-- Patrón de líneas SVG -->
  <div class="absolute inset-0 z-10 mix-blend-overlay pointer-events-none">
    <img src="/gridpattern.svg" alt="Patrón de líneas" class="w-full h-full object-cover" />
  </div>

  <!-- Hero / Banner contenido -->
  <section id="hero" class="relative z-20 text-white py-50">
    <div class="max-w-7xl mx-auto grid md:grid-cols-2 gap-20 items-center px-6">

      <!-- Lado izquierdo -->
      <div>
        <h1 class="text-6xl leading-tight font-bold mb-6">Portafolio Personal</h1>
        <p class="text-xl mb-6">Desarrollo de un portafolio web minimalista, responsivo y rápido, creado con Svelte y Tailwind CSS, desplegado en Vercel para mostrar mis proyectos, tecnologías y trayectoria profesional.</p>

        <div class="flex flex-wrap gap-2 mb-6">
          <span class="bg-cyan-100 text-cyan-800 text-m font-medium px-2.5 py-0.5 rounded">Frontend</span>
          <span class="bg-fuchsia-100 text-fuchsia-800 text-m font-medium px-2.5 py-0.5 rounded">UX/UI</span>
          <span class="bg-lime-100 text-lime-800 text-m font-medium px-2.5 py-0.5 rounded">Responsive</span>
          <span class="bg-indigo-100 text-indigo-800 text-m font-medium px-2.5 py-0.5 rounded">Despliegue Web</span>
        </div>

        <p class="text-m text-gray-300 mb-6">
          Industria: <span class="text-white font-bold">Tecnología</span> &nbsp;|&nbsp; Año: <span class="text-white font-bold">2025</span>
        </p>
      </div>

      <!-- Lado derecho -->
      <div class="space-y-4">
        <div class="hidden md:block">
          <div class="aspect-[4/3] overflow-hidden rounded-lg drop-shadow-2xl">
            <img src="/portafolio.png" alt="Portafolio Personal" class="object-cover w-full h-full" />
          </div>
        </div>
      </div>

    </div>
  </section>
</div>


<!-- Tecnologías -->
<section id="tecnologias" class="bg-gray-100 py-16 px-6">
  <div class="max-w-7xl mx-auto">
    <h2 class="text-4xl font-bold mb-15 text-[#062C70] text-center">Tecnologías Utilizadas</h2>
    <div class="grid grid-cols-2 md:grid-cols-3 gap-8 text-center">
      <div>
        <a href="https://svelte.dev/" target="_blank">
          <img src="/svelte.svg" alt="Svelte" class="h-20 mx-auto transition-transform duration-300 hover:scale-110">
          <p class="mt-2 font-medium">Svelte</p>
        </a>
      </div>
      <div>
        <a href="https://tailwindcss.com/" target="_blank">
          <img src="/tailwind.svg" alt="Tailwind CSS" class="h-20 mx-auto transition-transform duration-300 hover:scale-110">
          <p class="mt-2 font-medium">Tailwind CSS</p>
        </a>
      </div>
      <div>
        <a href="https://vercel.com/" target="_blank">
          <img src="/vercel.svg" alt="Vercel" class="h-20 mx-auto transition-transform duration-300 hover:scale-110">
          <p class="mt-2 font-medium">Vercel</p>
        </a>
      </div>
      <div>
        <a href="https://git-scm.com/" target="_blank">
          <img src="/git.svg" alt="Git" class="h-20 mx-auto transition-transform duration-300 hover:scale-110">
          <p class="mt-2 font-medium">Git</p>
        </a>
      </div>
      <div>
        <a href="https://vitejs.dev/" target="_blank">
          <img src="/vite.svg" alt="Vite" class="h-20 mx-auto transition-transform duration-300 hover:scale-110">
          <p class="mt-2 font-medium">Vite</p>
        </a>
      </div>
      <div>
        <a href="https://www.figma.com/" target="_blank">
          <img src="/figma.svg" alt="Figma" class="h-20 mx-auto transition-transform duration-300 hover:scale-110">
          <p class="mt-2 font-medium">Figma</p>
        </a>
      </div>
    </div>
  </div>
</section>

<!-- Funcionalidades -->
<section id="funcionalidades" class="py-16 max-w-7xl mx-auto px-6">
  <div class="grid md:grid-cols-2 gap-12 items-start">
    <div>
      <h2 class="text-4xl font-bold mb-6 text-[#062C70]">Funcionalidades Principales</h2>
      <p class="text-lg text-gray-700 leading-relaxed">
        Este proyecto permite centralizar y exhibir mis proyectos personales y profesionales de forma ordenada, responsiva y rápida, destacando tecnologías y experiencias relevantes en un solo sitio.
      </p>
    </div>

    <div class="grid sm:grid-cols-2 gap-6">
      <div class="cursor-default bg-white rounded-xl p-5 shadow hover:shadow-lg transition">
        <h3 class="text-xl font-semibold mb-2 text-[#062C70]">Diseño Minimalista</h3>
        <p class="text-gray-700 text-sm">Interfaz limpia, ordenada y con enfoque visual, adaptable a dispositivos móviles y escritorio.</p>
      </div>
      <div class="cursor-default bg-white rounded-xl p-5 shadow hover:shadow-lg transition">
        <h3 class="text-xl font-semibold mb-2 text-[#062C70]">Gestión de Proyectos</h3>
        <p class="text-gray-700 text-sm">Sección dinámica para publicar y organizar proyectos, tecnologías utilizadas y descripciones detalladas.</p>
      </div>
      <div class="cursor-default bg-white rounded-xl p-5 shadow hover:shadow-lg transition">
        <h3 class="text-xl font-semibold mb-2 text-[#062C70]">Optimización de Desempeño</h3>
        <p class="text-gray-700 text-sm">Desarrollo con Svelte y Vite para tiempos de carga mínimos y excelente rendimiento en Lighthouse.</p>
      </div>
      <div class="cursor-default bg-white rounded-xl p-5 shadow hover:shadow-lg transition">
        <h3 class="text-xl font-semibold mb-2 text-[#062C70]">Despliegue en Vercel</h3>
        <p class="text-gray-700 text-sm">Integración con Vercel para despliegues automáticos y entorno de hosting rápido y seguro.</p>
      </div>
      <div class="cursor-default bg-white rounded-xl p-5 shadow hover:shadow-lg transition sm:col-span-2">
        <h3 class="text-xl font-semibold mb-2 text-[#062C70]">Interacción y Animaciones</h3>
        <p class="text-gray-700 text-sm">Animaciones sutiles con Tailwind y transiciones suaves para una experiencia visual atractiva.</p>
      </div>
    </div>
  </div>
</section>

<!-- Galería -->
<section id="galeria" class="bg-gray-100 py-16">
  <div class="max-w-7xl mx-auto px-6">
    <div class="grid grid-cols-2 md:grid-cols-4 gap-8">

      <!-- Imagen principal (Home) -->
      <div class="col-span-2 md:col-span-2 overflow-hidden rounded-lg shadow-2xl">
        <img src="/portafolio_galeria.png" alt="Portafolio Home" class="w-full h-full object-cover rounded-lg" />
      </div>

      <!-- Responsive -->
      <div>
        <img src="/portafolio_responsive.png" alt="Responsive" class="w-full h-full object-cover rounded-lg shadow" />
      </div>
      <div>
        <img src="/portafolio_responsive2.png" alt="Responsive2" class="w-full h-full object-cover rounded-lg shadow" />
      </div>

      <!-- Proyectos (imagen grande) -->
      <div class="col-span-2 md:col-span-2">
        <img src="/portafolio_proyectos.png" alt="Proyectos" class="w-full h-full object-cover rounded-lg shadow" />
      </div>

      <!-- Servicios (imagen grande) -->
      <div class="col-span-2 md:col-span-2">
        <img src="/portafolio_servicios.png" alt="Servicios" class="w-full h-full object-cover rounded-lg shadow" />
      </div>

      <!-- Contacto (imagen grande) -->
      <div class="col-span-2 md:col-span-2">
        <img src="/portafolio_contacto.png" alt="Contacto" class="w-full h-full object-cover rounded-lg shadow" />
      </div>
      <!-- Contacto (imagen grande) -->
      <div class="col-span-2 md:col-span-2">
        <img src="/portafolio_home2.png" alt="Contacto" class="w-full h-full object-cover rounded-lg shadow" />
      </div>

    </div>
  </div>
</section>


<!-- Resultados y Aprendizajes -->
<section id="resultados" class="py-16 bg-[#062C70] text-white">
  <div class="max-w-7xl mx-auto px-6">
    <h2 class="text-3xl font-bold mb-12 text-center text-white">Resultados y Lecciones Aprendidas</h2>
    <div class="grid md:grid-cols-2 gap-8">
      <div class="cursor-default bg-white text-gray-800 rounded-xl p-6 shadow-lg ring-1 ring-blue-500/30 hover:ring-4 hover:ring-fuchsia-500/70 hover:shadow-2xl hover:scale-[1.02] transition duration-300">
        <h3 class="text-xl font-semibold mb-2">Portafolio Activo en Producción</h3>
        <p class="text-gray-700">Publicación estable en Vercel, disponible 24/7 y adaptable a cualquier dispositivo.</p>
      </div>
      <div class="cursor-default bg-white text-gray-800 rounded-xl p-6 shadow-lg ring-1 ring-blue-500/30 hover:ring-4 hover:ring-lime-400/70 hover:shadow-2xl hover:scale-[1.02] transition duration-300">
        <h3 class="text-xl font-semibold mb-2">Excelente Desempeño</h3>
        <p class="text-gray-700">Puntajes altos en Google Lighthouse en accesibilidad, SEO y performance.</p>
      </div>
      <div class="cursor-default bg-white text-gray-800 rounded-xl p-6 shadow-lg ring-1 ring-blue-500/30 hover:ring-4 hover:ring-amber-400/70 hover:shadow-2xl hover:scale-[1.02] transition duration-300">
        <h3 class="text-xl font-semibold mb-2">Mejora de Animaciones y UI</h3>
        <p class="text-gray-700">Implementación de animaciones sutiles, transiciones suaves y microinteracciones.</p>
      </div>
      <div class="cursor-default bg-white text-gray-800 rounded-xl p-6 shadow-lg ring-1 ring-blue-500/30 hover:ring-4 hover:ring-rose-500/70 hover:shadow-2xl hover:scale-[1.02] transition duration-300">
        <h3 class="text-xl font-semibold mb-2">Optimización de Workflow</h3>
        <p class="text-gray-700">Uso de Vite para un entorno de desarrollo ágil, con builds rápidos y hot-reloading eficiente.</p>
      </div>
    </div>
  </div>
</section>
