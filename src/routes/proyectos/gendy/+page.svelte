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
        <h1 class="text-6xl leading-tight font-bold mb-6">GENDY</h1>
        <p class="text-xl mb-6">Sistema de generación de horarios desarrollado en PHP con almacenamiento en MySQL y SQLite. Proyecto académico realizado en 2020.</p>

        <div class="flex flex-wrap gap-2 mb-6">
          <span class="bg-yellow-100 text-yellow-800 text-m font-medium px-2.5 py-0.5 rounded">Backend</span>
          <span class="bg-green-100 text-green-800 text-m font-medium px-2.5 py-0.5 rounded">Gestión de Datos</span>
          <span class="bg-pink-100 text-pink-800 text-m font-medium px-2.5 py-0.5 rounded">Interfaz Web</span>
        </div>

        <p class="text-m text-gray-300 mb-6">
          Industria: <span class="text-white font-bold">Tecnología</span> &nbsp;|&nbsp; Año: <span class="text-white font-bold">2020</span>
        </p>
      </div>

      <!-- Lado derecho -->
      <div class="space-y-6">
        <div class="hidden md:block">
          <div class="aspect-[4/3] overflow-hidden rounded-lg drop-shadow-2xl">
            <img src="/gendy_naranja.png" alt="GENDY" class="object-contain w-full h-full" />
          </div>
        </div>

        <!-- CTA debajo de la imagen -->
        <div class="text-center">
          <a href="https://github.com/Niser01/GENDY" target="_blank"
            class="inline-flex items-center gap-2 bg-blue-600 hover:bg-blue-700 text-white px-5 py-2 rounded-full transition">
            <img src="/github.svg" alt="GitHub" class="w-5 h-5" />
            Ver en GitHub
            <span class="text-lg">→</span>
          </a>
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
        <img src="/php.svg" alt="PHP" class="h-20 mx-auto transition-transform duration-300 hover:scale-110">
        <p class="mt-2 font-medium">PHP</p>
      </div>
      <div>
        <img src="/mysql.svg" alt="MySQL" class="h-20 mx-auto transition-transform duration-300 hover:scale-110">
        <p class="mt-2 font-medium">MySQL</p>
      </div>
      <div>
        <img src="/sqlite.svg" alt="SQLite" class="h-20 mx-auto transition-transform duration-300 hover:scale-110">
        <p class="mt-2 font-medium">SQLite</p>
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
        GENDY permite a los usuarios generar horarios académicos personalizados según disponibilidad de cursos y restricciones horarias, almacenando la información de forma segura en bases de datos relacionales. 
        Participé en este proyecto como parte de un equipo académico, colaborando en el desarrollo backend con PHP y gestionando las operaciones CRUD para el almacenamiento y consulta de horarios.
      </p>
    </div>

    <div class="grid sm:grid-cols-2 gap-6">
      <div class="cursor-default bg-white rounded-xl p-5 shadow hover:shadow-lg transition">
        <h3 class="text-xl font-semibold mb-2 text-[#062C70]">Generación de Horarios</h3>
        <p class="text-gray-700 text-sm">Algoritmo que permite asignar cursos según disponibilidad de franjas horarias.</p>
      </div>
      <div class="cursor-default bg-white rounded-xl p-5 shadow hover:shadow-lg transition">
        <h3 class="text-xl font-semibold mb-2 text-[#062C70]">Gestión CRUD</h3>
        <p class="text-gray-700 text-sm">Alta, consulta, modificación y eliminación de horarios, cursos y usuarios registrados.</p>
      </div>
      <div class="cursor-default bg-white rounded-xl p-5 shadow hover:shadow-lg transition">
        <h3 class="text-xl font-semibold mb-2 text-[#062C70]">Almacenamiento Dual</h3>
        <p class="text-gray-700 text-sm">Persistencia de datos en MySQL para entorno de servidor y SQLite en entornos locales.</p>
      </div>
      <div class="cursor-default bg-white rounded-xl p-5 shadow hover:shadow-lg transition">
        <h3 class="text-xl font-semibold mb-2 text-[#062C70]">Interfaz Web</h3>
        <p class="text-gray-700 text-sm">Interfaz simple desarrollada en PHP para interacción de usuario final y validación de horarios.</p>
      </div>
    </div>
  </div>
</section>

<!-- Galería -->
<section id="galeria" class="bg-gray-100 py-16">
  <div class="max-w-7xl mx-auto px-6">
    <div class="grid grid-cols-2 md:grid-cols-4 gap-8">
      <div>
        <img src="/gendy_home.png" alt="Pantalla principal" class="w-full h-full object-cover rounded-lg shadow" />
      </div>
      <div>
        <img src="/gendy_generar.png" alt="Generar horario" class="w-full h-full object-cover rounded-lg shadow" />
      </div>
      <div>
        <img src="/gendy_horarios.png" alt="Ver horarios" class="w-full h-full object-cover rounded-lg shadow" />
      </div>
      <div>
        <img src="/gendy_admin.png" alt="Gestión de cursos" class="w-full h-full object-cover rounded-lg shadow" />
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
        <h3 class="text-xl font-semibold mb-2">Sistema Funcional</h3>
        <p class="text-gray-700">Entrega de una solución académica completa, operativa y desplegable en entornos educativos.</p>
      </div>
      <div class="cursor-default bg-white text-gray-800 rounded-xl p-6 shadow-lg ring-1 ring-blue-500/30 hover:ring-4 hover:ring-lime-400/70 hover:shadow-2xl hover:scale-[1.02] transition duration-300">
        <h3 class="text-xl font-semibold mb-2">Gestión Eficiente de Datos</h3>
        <p class="text-gray-700">Aprendizaje sobre integración dual de bases de datos y optimización de consultas en PHP.</p>
      </div>
    </div>
  </div>
</section>
