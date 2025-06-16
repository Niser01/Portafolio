<!-- Hero / Banner -->
<section id="hero" class="bg-[#062C70] text-white py-50">
  <div class="max-w-7xl mx-auto grid md:grid-cols-2 gap-20 items-center px-6">
    <!-- Lado izquierdo -->
    <div>
      <h1 class="text-6xl leading-tight font-bold mb-6">CADUN</h1>
      <p class="text-xl mb-6">API de consulta de datos de usuarios universitarios desarrollada en Go con despliegue en Docker y PostgreSQL. Proyecto académico realizado en 2024.</p>
        <div class="flex flex-wrap gap-2 mb-6">
        <span class="bg-yellow-100 text-yellow-800 text-m font-medium px-2.5 py-0.5 rounded">Backend</span>
        <span class="bg-green-100 text-green-800 text-m font-medium px-2.5 py-0.5 rounded">API REST</span>
        <span class="bg-rose-100 text-rose-800 text-m font-medium px-2.5 py-0.5 rounded">Base de Datos</span>
        <span class="bg-blue-100 text-blue-800 text-m font-medium px-2.5 py-0.5 rounded">Contenerización</span>
        </div>
      <p class="text-m text-gray-300 mb-6">
        Industria: <span class="text-white font-bold">Tecnología</span> &nbsp;|&nbsp; Año: <span class="text-white font-bold">2024</span>
      </p>
    </div>
    <!-- Lado derecho -->
    <div class="space-y-6">
      <div class="hidden md:block">
        <div class="aspect-[4/3] overflow-hidden rounded-lg drop-shadow-2xl">
          <img src="/cadun.png" alt="CADUN" class="object-contain w-full h-full" />
        </div>
      </div>
      <!-- CTA debajo de la imagen -->
      <div class="text-center">
        <a href="https://github.com/Niser01/CADUN_Users" target="_blank"
          class="inline-flex items-center gap-2 bg-blue-600 hover:bg-blue-700 text-white px-5 py-2 rounded-full transition">
          <img src="/github.svg" alt="GitHub" class="w-5 h-5" />
          Ver en GitHub
          <span class="text-lg">→</span>
        </a>
      </div>
    </div>
  </div>
</section>

<!-- Tecnologías -->
<section id="tecnologias" class="bg-gray-100 py-16 px-6">
  <div class="max-w-7xl mx-auto">
    <h2 class="text-4xl font-bold mb-15 text-[#062C70] text-center">Tecnologías Utilizadas</h2>
    <div class="grid grid-cols-2 md:grid-cols-4 gap-8 text-center">
      <div>
        <img src="/go.svg" alt="Go" class="h-20 mx-auto transition-transform duration-300 hover:scale-110">
        <p class="mt-2 font-medium">Go</p>
      </div>
      <div>
        <img src="/echo.svg" alt="Echo" class="h-20 mx-auto transition-transform duration-300 hover:scale-110">
        <p class="mt-2 font-medium">Echo</p>
      </div>
      <div>
        <img src="/docker.svg" alt="Docker" class="h-20 mx-auto transition-transform duration-300 hover:scale-110">
        <p class="mt-2 font-medium">Docker</p>
      </div>
      <div>
        <img src="/postgresql.svg" alt="PostgreSQL" class="h-20 mx-auto transition-transform duration-300 hover:scale-110">
        <p class="mt-2 font-medium">PostgreSQL</p>
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
        CADUN proporciona una API RESTful que permite realizar operaciones CRUD sobre datos de usuarios universitarios, diseñada para ser desplegada de manera local mediante Docker. Participé en este proyecto desarrollando el backend en Go con el framework Echo, gestionando la estructura de la base de datos en PostgreSQL y configurando los contenedores Docker para un despliegue portátil.
      </p>
    </div>

    <div class="grid sm:grid-cols-2 gap-6">
      <div class="cursor-default bg-white rounded-xl p-5 shadow hover:shadow-lg transition">
        <h3 class="text-xl font-semibold mb-2 text-[#062C70]">API RESTful</h3>
        <p class="text-gray-700 text-sm">Diseño y desarrollo de endpoints para la gestión de usuarios universitarios.</p>
      </div>
      <div class="cursor-default bg-white rounded-xl p-5 shadow hover:shadow-lg transition">
        <h3 class="text-xl font-semibold mb-2 text-[#062C70]">Despliegue en Docker</h3>
        <p class="text-gray-700 text-sm">Contenerización de la aplicación para su ejecución portátil y sin dependencias externas.</p>
      </div>
      <div class="cursor-default bg-white rounded-xl p-5 shadow hover:shadow-lg transition">
        <h3 class="text-xl font-semibold mb-2 text-[#062C70]">Persistencia en PostgreSQL</h3>
        <p class="text-gray-700 text-sm">Gestión de una base de datos relacional robusta para almacenar información de usuarios.</p>
      </div>
      <div class="cursor-default bg-white rounded-xl p-5 shadow hover:shadow-lg transition">
        <h3 class="text-xl font-semibold mb-2 text-[#062C70]">Framework Echo</h3>
        <p class="text-gray-700 text-sm">Uso de Echo para estructurar las rutas, middlewares y controladores de la API en Go.</p>
      </div>
    </div>
  </div>
</section>

<!-- Resultados y Lecciones -->
<section id="resultados" class="py-16 bg-[#062C70] text-white">
  <div class="max-w-7xl mx-auto px-6">
    <h2 class="text-3xl font-bold mb-12 text-center text-white">Resultados y Lecciones Aprendidas</h2>
    <div class="grid md:grid-cols-2 gap-8">
      <div class="cursor-default bg-white text-gray-800 rounded-xl p-6 shadow-lg ring-1 ring-blue-500/30 hover:ring-4 hover:ring-fuchsia-500/70 hover:shadow-2xl hover:scale-[1.02] transition duration-300">
        <h3 class="text-xl font-semibold mb-2">API Modular y Escalable</h3>
        <p class="text-gray-700">Se logró una arquitectura de API limpia, modular y fácilmente escalable, ideal para aplicaciones académicas o de gestión institucional.</p>
      </div>
      <div class="cursor-default bg-white text-gray-800 rounded-xl p-6 shadow-lg ring-1 ring-blue-500/30 hover:ring-4 hover:ring-lime-400/70 hover:shadow-2xl hover:scale-[1.02] transition duration-300">
        <h3 class="text-xl font-semibold mb-2">Manejo de Despliegue en Contenedores</h3>
        <p class="text-gray-700">Adquisición de experiencia en la creación y despliegue de microservicios utilizando Docker y administración de bases de datos PostgreSQL.</p>
      </div>
    </div>
  </div>
</section>
