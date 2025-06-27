<div class="relative overflow-hidden">
  <!-- Fondo gradiente -->
  <div class="absolute inset-0 z-0" style="background: linear-gradient(-66deg, #140544 0%, #0F172A 100%);"></div>

  <!-- Patrón de líneas SVG -->
  <div class="absolute inset-0 z-10 mix-blend-overlay pointer-events-none">
    <img src="/gridpattern.svg" alt="Patrón de líneas" class="w-full h-full object-cover" />
  </div>

  <!-- Hero con CTA -->
  <section id="hero" class="relative z-20 text-white py-50">
    <div class="max-w-7xl mx-auto grid md:grid-cols-2 gap-20 items-center px-6">
      <div>
        <h1 class="text-6xl leading-tight font-bold mb-6">Pack&Track</h1>
        <p class="text-xl mb-6">Sistema de seguimiento de paquetes en tiempo real y gestión de entregas para optimizar procesos logísticos y mejorar la trazabilidad de envíos.</p>
        <div class="flex flex-wrap gap-2 mb-6">
          <span class="bg-cyan-100 text-cyan-800 text-m font-medium px-2.5 py-0.5 rounded">DataBase</span>
          <span class="bg-rose-100 text-rose-800 text-m font-medium px-2.5 py-0.5 rounded">Backend</span>
          <span class="bg-indigo-100 text-indigo-800 text-m font-medium px-2.5 py-0.5 rounded">Frontend</span>
          <span class="bg-amber-100 text-amber-800 text-m font-medium px-2.5 py-0.5 rounded">Cloud Hosting</span>
        </div>
        <p class="text-m text-gray-300 mb-6">
          Industria: <span class="text-white font-bold">Logística</span> &nbsp;|&nbsp; Año: <span class="text-white font-bold">2025</span>
        </p>
      </div>

      <div class="space-y-6">
        <div class="hidden md:block">
          <div class="aspect-[4/3] overflow-hidden rounded-lg drop-shadow-2xl">
            <img src="/P&T_Blanco.svg" alt="Pack&Track App" class="object-contain w-full h-full" />
          </div>
        </div>

      <!-- CTA doble -->
      <div class="flex flex-col items-center gap-3">
        <a href="https://github.com/Niser01/RegistroYSeguimientoDeEnvios" target="_blank"
          class="inline-flex items-center justify-center gap-2 bg-blue-600 hover:bg-blue-700 text-white px-4 py-2 rounded-full transition text-sm w-56">
          <img src="/github.svg" alt="GitHub" class="w-4 h-4" />
          Ver en GitHub
          <span class="text-base">→</span>
        </a>

        <a href="https://registro-y-seguimiento-de-envios.vercel.app/" target="_blank"
          class="inline-flex items-center justify-center gap-2 bg-green-600 hover:bg-green-700 text-white px-4 py-2 rounded-full transition text-sm w-56">
          <img src="/packtrack_icon.svg" alt="PackTrack" class="w-4 h-4" />
          Ver en Vivo
          <span class="text-base">→</span>
        </a>
      </div>


      </div>
    </div>
  </section>
</div>

<!-- Tecnologías -->
<section class="bg-gray-100 py-16 px-6">
  <div class="max-w-7xl mx-auto">
    <h2 class="text-4xl font-bold mb-15 text-[#062C70] text-center">Tecnologías Utilizadas</h2>
    <div class="grid grid-cols-2 md:grid-cols-3 gap-8 text-center">
      <div><img src="/postgresql.svg" alt="PostgreSQL" class="h-20 mx-auto hover:scale-110 transition" /><p class="mt-2 font-medium">PostgreSQL</p></div>
      <div><img src="/go.svg" alt="Go" class="h-20 mx-auto hover:scale-110 transition" /><p class="mt-2 font-medium">Go</p></div>
      <div><img src="/svelte.svg" alt="Svelte" class="h-20 mx-auto hover:scale-110 transition" /><p class="mt-2 font-medium">Svelte</p></div>
      <div><img src="/neon.svg" alt="Neon" class="h-20 mx-auto hover:scale-110 transition" /><p class="mt-2 font-medium">Neon</p></div>
      <div><img src="/render.svg" alt="Render" class="h-20 mx-auto hover:scale-110 transition" /><p class="mt-2 font-medium">Render</p></div>
      <div><img src="/vercel.svg" alt="Vercel" class="h-20 mx-auto hover:scale-110 transition" /><p class="mt-2 font-medium">Vercel</p></div>    
    </div>
  </div>
</section>

<!-- Descripción del Proyecto -->
<section class="py-16 max-w-7xl mx-auto px-6 bg-white">
  <div class="text-center">
    <h2 class="text-4xl font-bold mb-6 text-[#062C70]">Sobre el Proyecto</h2>
    <p class="text-lg text-gray-700 leading-relaxed">
      <strong>Pack&Track</strong> es una empresa ficticia creada únicamente con fines demostrativos. Este proyecto forma parte de mi portafolio personal, desarrollado para exponer mis habilidades como desarrollador <strong>fullstack</strong>, abarcando desde el diseño del frontend hasta la implementación de un backend funcional y seguro.
      <br/><br/>
      Cabe aclarar que cualquier similitud con empresas reales, nombres comerciales o marcas es pura coincidencia. No se persigue con este trabajo apropiarse de la imagen, identidad o propiedad intelectual de ninguna entidad existente.
    </p>
  </div>
</section>


<!-- Funcionalidades -->
<section class="bg-white py-16">
  <div class="max-w-7xl mx-auto px-6">
    <div class="grid md:grid-cols-2 gap-12 items-start">
      <div>
        <h2 class="text-4xl font-bold mb-6 text-[#062C70]">Funcionalidades Principales</h2>
        <p class="text-lg text-gray-700 leading-relaxed">Pack&Track permite a los usuarios registrar paquetes, consultar su ubicación en tiempo real y gestionar el ciclo de entrega desde una interfaz web responsiva, conectada a un backend escalable y seguro.</p>
      </div>
      <div class="grid sm:grid-cols-2 gap-6">
        <!-- Tarjetas -->
        <div class="bg-white rounded-xl p-5 shadow hover:shadow-lg transition">
          <h3 class="text-xl font-semibold mb-2 text-[#062C70]">Registro de Envíos</h3>
          <p class="text-gray-700 text-sm">Formulario para ingresar paquetes con información detallada.</p>
        </div>
        <div class="bg-white rounded-xl p-5 shadow hover:shadow-lg transition">
          <h3 class="text-xl font-semibold mb-2 text-[#062C70]">Tracking en Tiempo Real</h3>
          <p class="text-gray-700 text-sm">Consulta de estado y ubicación a través de API.</p>
        </div>
        <div class="bg-white rounded-xl p-5 shadow hover:shadow-lg transition">
          <h3 class="text-xl font-semibold mb-2 text-[#062C70]">Gestión de Entregas</h3>
          <p class="text-gray-700 text-sm">Confirmación de entregas con registro de datos.</p>
        </div>
        <div class="bg-white rounded-xl p-5 shadow hover:shadow-lg transition">
          <h3 class="text-xl font-semibold mb-2 text-[#062C70]">Dashboard de Reportes</h3>
          <p class="text-gray-700 text-sm">Estadísticas de entregas y paquetes en tránsito.</p>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- Ejemplo de Tracking Number -->
<section class="bg-gray-100 py-16">
  <div class="max-w-7xl mx-auto px-6">
    <h2 class="text-3xl font-bold mb-8 text-[#062C70] text-center">Ejemplo de Número de Seguimiento</h2>
    <div class="bg-gray-50 p-6 rounded-xl shadow-md text-center max-w-xl mx-auto">
      <p class="text-lg text-gray-700 mb-4">Puedes probar la funcionalidad de tracking usando:</p>
      <div class="text-2xl font-bold text-[#062C70] tracking-widest select-all">TRK123456</div>
      <p class="text-sm text-gray-500 mt-3">Ingresa este código en el buscador de paquetes para ver su estado actual.</p>
    </div>
  </div>
</section>


<!-- Sección futura -->
<section class="bg-white py-16">
  <div class="max-w-7xl mx-auto px-6">
    <h2 class="text-3xl font-bold mb-8 text-[#062C70] text-center">Gestión de Envíos</h2>
    <p class="text-lg text-gray-600 text-center">Esta sección se encuentra en desarrollo. Permitirá administrar paquetes, actualizar estados y visualizar historial de envíos.</p>
  </div>
</section>


<!-- Galería -->
<section class="bg-gray-100 py-16">
  <div class="max-w-7xl mx-auto px-6">
    <div class="grid grid-cols-2 md:grid-cols-4 gap-8">
      <div class="col-span-2 md:col-span-2 row-span-2 overflow-hidden rounded-lg shadow-2xl">
        <img src="/packtrack_main.png" alt="Vista general" class="w-full h-full object-cover rounded-lg" />
      </div>
      <div><img src="/packtrack_envios.png" alt="Envíos" class="w-full h-full object-fill rounded-lg shadow" /></div>
      <div><img src="/packtrack_tracking.png" alt="Tracking" class="w-full h-full object-fill rounded-lg shadow" /></div>
      <div class="col-span-2"><img src="/packtrack_dashboard.png" alt="Dashboard" class="w-full h-full object-fill rounded-lg shadow" /></div>
    </div>
  </div>
</section>

<!-- Resultados -->
<section class="py-16 bg-[#062C70] text-white">
  <div class="max-w-7xl mx-auto px-6">
    <h2 class="text-3xl font-bold mb-12 text-center">Resultados y Lecciones Aprendidas</h2>
    <div class="grid md:grid-cols-2 gap-8">
      <div class="bg-white text-gray-800 rounded-xl p-6 shadow-lg ring-1 ring-blue-500/30 hover:ring-4 hover:ring-fuchsia-500/70 hover:scale-[1.02] transition">
        <h3 class="text-xl font-semibold mb-2">API Eficiente y Escalable</h3>
        <p class="text-gray-700">Backend en Go manejando +500 peticiones concurrentes.</p>
      </div>
      <div class="bg-white text-gray-800 rounded-xl p-6 shadow-lg ring-1 ring-blue-500/30 hover:ring-4 hover:ring-lime-400/70 hover:scale-[1.02] transition">
        <h3 class="text-xl font-semibold mb-2">Despliegue Cloud</h3>
        <p class="text-gray-700">Frontend en Vercel, Backend en Render, DB en Neon.</p>
      </div>
      <div class="bg-white text-gray-800 rounded-xl p-6 shadow-lg ring-1 ring-blue-500/30 hover:ring-4 hover:ring-amber-400/70 hover:scale-[1.02] transition">
        <h3 class="text-xl font-semibold mb-2">Interfaz Ágil y Clara</h3>
        <p class="text-gray-700">Frontend responsivo en Svelte para móvil y escritorio.</p>
      </div>
      <div class="bg-white text-gray-800 rounded-xl p-6 shadow-lg ring-1 ring-blue-500/30 hover:ring-4 hover:ring-rose-500/70 hover:scale-[1.02] transition">
        <h3 class="text-xl font-semibold mb-2">Gestión de Proyecto</h3>
        <p class="text-gray-700">Control de versión y despliegue automatizado vía Git.</p>
      </div>
    </div>
  </div>
</section>
