<section id="hero" class="relative min-h-[70vh] md:min-h-screen flex items-center justify-center text-white overflow-hidden">
  <!-- Fondo gradiente CSS -->
  <div class="absolute inset-0 z-0" style="background: linear-gradient(-66deg, #140544 0%, #0F172A 100%);"></div>

  <!-- Patrón de líneas SVG encima -->
  <div class="absolute inset-0 z-1 opacity-20">
    <img src="/grid-pattern.svg" alt="Patrón de líneas" class="w-full h-full object-cover" />
  </div>

  <!-- Glow decorativo -->
  <div class="absolute w-[500px] h-[500px] rounded-full z-2 bottom-0 right-10 pointer-events-none">
    <img src="/glow-circle.png" alt="Glow decorativo" class="w-full h-full" />
  </div>

  <!-- Contenido principal -->
  <div class="w-full flex flex-col md:flex-row h-full relative z-4 max-w-7xl mx-auto px-4 py-12 md:py-0 items-center">
    
    <!-- Texto -->
    <div class="text-white w-full md:w-1/2 flex flex-col justify-center h-full space-y-6 text-center md:text-left">
      <div>
        <p class="text-[24px] md:text-[32px] font-normal">¡Hola! Soy Nicolás,</p>
        <h1 class="text-[32px] md:text-[45px] font-extrabold leading-tight bg-gradient-to-r from-[#33AAFF] to-[#D711FF] bg-clip-text text-transparent">
          Desarrollador de Software
        </h1>
        <p class="text-gray-300 text-[16px] md:text-[18px] mt-4">
          Diseño y desarrollo soluciones digitales eficientes para potenciar tus ideas.
        </p>
      </div>

      <!-- CTA -->
      <div>
        <a href="/servicios" class="inline-block bg-blue-600 hover:bg-blue-700 text-white font-bold text-[16px] md:text-[18px] px-6 py-3 rounded-full transition">
          Ver Servicios →
        </a>
      </div>
    </div>

    <!-- Laptop -->
    <div class="md:w-1/2 h-full flex items-center justify-center relative mt-16 md:mt-0 hidden md:flex z-3">
      <img src="/laptop.png" alt="Laptop" class="w-full max-w-lg mx-auto" />
    </div>

  </div>
</section>




<section id="tecnologias" class="flex flex-col items-center bg-white px-4 py-20 max-w-7xl mx-auto border-t border-gray-200">
  <h2 class="text-4xl font-bold mb-8 text-center">Tecnologías utilizadas</h2>
  <div class="relative overflow-hidden w-full py-4 group">
    <div class="flex space-x-16 animate-slide whitespace-nowrap w-max">
      <!-- Primera tanda -->
      <a href="https://www.python.org/" target="_blank" rel="noopener noreferrer">
        <img src="/python.svg" alt="Python" class="h-20 transition-transform duration-300 hover:scale-125">
      </a>
      <a href="https://www.djangoproject.com/" target="_blank" rel="noopener noreferrer">
        <img src="/django.svg" alt="Django" class="h-20 transition-transform duration-300 hover:scale-125">
      </a>
      <a href="https://go.dev/" target="_blank" rel="noopener noreferrer">
        <img src="/go.svg" alt="GoLang" class="h-20 transition-transform duration-300 hover:scale-125">
      </a>
      <a href="https://www.docker.com/" target="_blank" rel="noopener noreferrer">
        <img src="/docker.svg" alt="Docker" class="h-20 transition-transform duration-300 hover:scale-125">
      </a>
      <a href="https://graphql.org/" target="_blank" rel="noopener noreferrer">
        <img src="/graphql.svg" alt="GraphQl" class="h-20 transition-transform duration-300 hover:scale-125">
      </a>
      <a href="https://vercel.com/" target="_blank" rel="noopener noreferrer">
        <img src="/vercel.svg" alt="Vercel" class="h-20 transition-transform duration-300 hover:scale-125">
      </a>
      <a href="https://cloud.google.com/" target="_blank" rel="noopener noreferrer">
        <img src="/googlecloud.svg" alt="Google Cloud" class="h-20 transition-transform duration-300 hover:scale-125">
      </a>
      <a href="https://www.postgresql.org/" target="_blank" rel="noopener noreferrer">
        <img src="/postgresql.svg" alt="PostgreSQL" class="h-20 transition-transform duration-300 hover:scale-125">
      </a>
      <a href="https://git-scm.com/" target="_blank" rel="noopener noreferrer">
        <img src="/git.svg" alt="Git" class="h-20 transition-transform duration-300 hover:scale-125">
      </a>
      <a href="https://svelte.dev/" target="_blank" rel="noopener noreferrer">
        <img src="/svelte.svg" alt="Svelte" class="h-20 transition-transform duration-300 hover:scale-125">
      </a>
      <a href="https://wordpress.org/" target="_blank" rel="noopener noreferrer">
        <img src="/wordpress.svg" alt="WordPress" class="h-20 transition-transform duration-300 hover:scale-125">
      </a>

      <!-- Segunda tanda (idéntica para que el loop sea fluido) -->
      <a href="https://www.python.org/" target="_blank" rel="noopener noreferrer">
        <img src="/python.svg" alt="Python" class="h-20 transition-transform duration-300 hover:scale-125">
      </a>
      <a href="https://www.djangoproject.com/" target="_blank" rel="noopener noreferrer">
        <img src="/django.svg" alt="Django" class="h-20 transition-transform duration-300 hover:scale-125">
      </a>
      <a href="https://go.dev/" target="_blank" rel="noopener noreferrer">
        <img src="/go.svg" alt="GoLang" class="h-20 transition-transform duration-300 hover:scale-125">
      </a>
      <a href="https://www.docker.com/" target="_blank" rel="noopener noreferrer">
        <img src="/docker.svg" alt="Docker" class="h-20 transition-transform duration-300 hover:scale-125">
      </a>
      <a href="https://graphql.org/" target="_blank" rel="noopener noreferrer">
        <img src="/graphql.svg" alt="GraphQl" class="h-20 transition-transform duration-300 hover:scale-125">
      </a>
      <a href="https://vercel.com/" target="_blank" rel="noopener noreferrer">
        <img src="/vercel.svg" alt="Vercel" class="h-20 transition-transform duration-300 hover:scale-125">
      </a>
      <a href="https://cloud.google.com/" target="_blank" rel="noopener noreferrer">
        <img src="/googlecloud.svg" alt="Google Cloud" class="h-20 transition-transform duration-300 hover:scale-125">
      </a>
      <a href="https://www.postgresql.org/" target="_blank" rel="noopener noreferrer">
        <img src="/postgresql.svg" alt="PostgreSQL" class="h-20 transition-transform duration-300 hover:scale-125">
      </a>
      <a href="https://git-scm.com/" target="_blank" rel="noopener noreferrer">
        <img src="/git.svg" alt="Git" class="h-20 transition-transform duration-300 hover:scale-125">
      </a>
      <a href="https://svelte.dev/" target="_blank" rel="noopener noreferrer">
        <img src="/svelte.svg" alt="Svelte" class="h-20 transition-transform duration-300 hover:scale-125">
      </a>
      <a href="https://wordpress.org/" target="_blank" rel="noopener noreferrer">
        <img src="/wordpress.svg" alt="WordPress" class="h-20 transition-transform duration-300 hover:scale-125">
      </a>
    </div>
  </div>
</section>

<section id="proyectos" class="flex flex-col items-center bg-white px-4 py-20 max-w-7xl mx-auto border-t border-gray-200">
  <h2 class="text-4xl font-bold mb-4 text-center">Proyectos destacados</h2>
  <p class="text-gray-600 mb-12 text-lg text-center">Algunos de los proyectos más relevantes en los que he trabajado. ¿Quieres conocer más?</p>
  <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8 w-full">

    <!-- Proyecto 1 -->
    <div class="border rounded-2xl p-6 shadow-lg hover:scale-105 transition bg-white">
      <img src="/todolist.svg" alt="To-Do List App" class="rounded-lg mb-4 h-48 w-full object-contain">
      <h3 class="text-2xl font-semibold mb-2">To-Do List App</h3>
      <p class="text-gray-600 mb-3">App de tareas fullstack en desarrollo con Go, PostgreSQL y GraphQL, con frontend planeado en Svelte y API Gateway propio.</p>
      <div class="flex flex-wrap gap-2 mb-4">
        <span class="bg-teal-100 text-teal-800 text-xs font-medium px-2.5 py-0.5 rounded">Go</span>
        <span class="bg-indigo-100 text-indigo-800 text-xs font-medium px-2.5 py-0.5 rounded">PostgreSQL</span>
        <span class="bg-purple-100 text-purple-800 text-xs font-medium px-2.5 py-0.5 rounded">GraphQL</span>
        <span class="bg-pink-100 text-pink-800 text-xs font-medium px-2.5 py-0.5 rounded">Svelte</span>
      </div>
      <a href="https://github.com/Niser01/API-ToDo-List" target="_blank" class="text-blue-600 hover:underline">Ver en GitHub →</a>
    </div>

    <!-- Proyecto 2 -->
    <div class="border rounded-2xl p-6 shadow-lg hover:scale-105 transition bg-white">
      <img src="/portafolio.png" alt="Portafolio Personal" class="rounded-lg mb-4 h-48 w-full object-cover">
      <h3 class="text-2xl font-semibold mb-2">Portafolio Personal</h3>
      <p class="text-gray-600 mb-3">Mi portafolio web minimalista, rápido y responsivo desarrollado con Svelte y Tailwind CSS, alojado en Vercel.</p>
      <div class="flex flex-wrap gap-2 mb-4">
        <span class="bg-pink-100 text-pink-800 text-xs font-medium px-2.5 py-0.5 rounded">Svelte</span>
        <span class="bg-blue-100 text-blue-800 text-xs font-medium px-2.5 py-0.5 rounded">Tailwind</span>
        <span class="bg-gray-100 text-gray-800 text-xs font-medium px-2.5 py-0.5 rounded">Vercel</span>
      </div>
      <a href="/proyectos/portafolio" class="text-blue-600 hover:underline">Ver más →</a>
    </div>

    <!-- Proyecto 3 -->
    <div class="border rounded-2xl p-6 shadow-lg hover:scale-105 transition bg-white">
      <img src="/facultad_ciencias.png" alt="Facultad Ciencias" class="rounded-lg mb-4 h-48 w-full object-cover">
      <h3 class="text-2xl font-semibold mb-2">Página Web Facultad de Ciencias - UNAL</h3>
      <p class="text-gray-600 mb-3">Sitio institucional desarrollado y desplegado con rediseño completo y migración de contenidos.</p>
      <div class="flex flex-wrap gap-2 mb-4">
        <span class="bg-blue-100 text-blue-800 text-xs font-medium px-2.5 py-0.5 rounded">HTML</span>
        <span class="bg-yellow-100 text-yellow-800 text-xs font-medium px-2.5 py-0.5 rounded">CSS</span>
        <span class="bg-green-100 text-green-800 text-xs font-medium px-2.5 py-0.5 rounded">WordPress</span>
        <span class="bg-gray-200 text-gray-800 text-xs font-medium px-2.5 py-0.5 rounded">Apache</span>
      </div>
      <a href="/proyectos/pagina_web_facultad_de_ciencias" class="text-blue-600 hover:underline">Ver más →</a>
    </div>

  </div>

  <!-- Botón para ver todos -->
  <div class="mt-12 w-full flex justify-center">
    <a href="/proyectos" class="inline-block bg-blue-600 text-white text-lg font-medium px-6 py-3 rounded-full shadow-lg hover:bg-blue-700 transition">
      Ver todos los proyectos →
    </a>
  </div>
</section>

<section id="servicios" class="bg-[#062C70] text-white px-4 py-24">
  <div class="max-w-7xl mx-auto text-center">
    <h2 class="text-4xl font-bold mb-8">¿Qué puedo hacer por ti?</h2>

    <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
      <!-- Servicio 1 -->
      <div class="bg-white text-[#0F172A] p-8 rounded-2xl shadow-lg hover:scale-105 transition">
        <div class="flex items-center justify-center w-16 h-16 mx-auto mb-6 rounded-full bg-blue-100 text-blue-600">
          <i class="fa-solid fa-code text-2xl"></i>
        </div>
        <h3 class="text-2xl font-bold mb-2">Web & Frontend</h3>
        <p class="text-gray-600">Landing pages, dashboards y sistemas responsivos optimizados para SEO y rendimiento.</p>
      </div>

      <!-- Servicio 2 -->
      <div class="bg-white text-[#0F172A] p-8 rounded-2xl shadow-lg hover:scale-105 transition">
        <div class="flex items-center justify-center w-16 h-16 mx-auto mb-6 rounded-full bg-green-100 text-green-600">
          <i class="fa-solid fa-server text-2xl"></i>
        </div>
        <h3 class="text-2xl font-bold mb-2">APIs & Backend</h3>
        <p class="text-gray-600">Servicios robustos en Python, Go, GraphQL y REST, listos para escalar en nube o contenedores.</p>
      </div>

      <!-- Servicio 3 -->
      <div class="bg-white text-[#0F172A] p-8 rounded-2xl shadow-lg hover:scale-105 transition">
        <div class="flex items-center justify-center w-16 h-16 mx-auto mb-6 rounded-full bg-purple-100 text-purple-600">
          <i class="fa-solid fa-gears text-2xl"></i>
        </div>
        <h3 class="text-2xl font-bold mb-2">Infraestructura & DevOps</h3>
        <p class="text-gray-600">Automatización de despliegues, Dockerización de apps y configuración de servidores cloud.</p>
      </div>
    </div>

    <div class="mt-12">
      <a href="/servicios" class="inline-block bg-blue-600 hover:bg-blue-700 text-white px-8 py-3 rounded-full text-lg font-semibold transition">Ver servicios detallados →</a>
    </div>
  </div>
</section>


<section id="sobremi" class="bg-gray-50 py-24 border-t border-gray-200">
  <div class="max-w-7xl w-full mx-auto grid grid-cols-1 md:grid-cols-2 gap-12 items-center px-4">
    
    <!-- Texto -->
    <div class="text-center md:text-left space-y-4">
      <h2 class="text-4xl font-bold mb-6">Sobre mí</h2>
      <p class="text-gray-700 mb-4">
        Soy <span class="font-semibold">Nicolás Haldane</span>, Ingeniero de Sistemas graduado de la Universidad Nacional de Colombia.
        Apasionado por el desarrollo backend, microservicios, cloud y automatización.
        Me encanta diseñar soluciones eficientes y bien estructuradas.
      </p>
      
      <!-- Educación -->
      <div class="mb-6">
        <h3 class="text-2xl font-semibold mb-2">🎓 Educación</h3>
        <ul class="list-disc list-inside text-gray-700">
          <li>Ingeniero de Sistemas y Computación — UNAL (2024)</li>
        </ul>
      </div>

      <!-- Experiencia -->
      <div>
        <h3 class="text-2xl font-semibold mb-2">💼 Experiencia</h3>
        <ul class="list-disc list-inside text-gray-700">
          <li>Desarrollador — Infometrika S.A.S (2025)</li>
          <li>Contratista TI — Facultad de Ciencias UNAL (2024)</li>
          <li>Estudiante Auxiliar Web — UNAL (2021-2024)</li>
        </ul>
      </div>
    </div>

    <!-- Foto -->
    <div class="flex justify-center hidden md:flex">
      <img src="/SergioNicolas.jpg" alt="Foto de Nicolás" class="rounded-2xl shadow-lg w-80 h-80 object-cover">
    </div>

  </div>
</section>

