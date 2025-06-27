<script>
  import { onMount } from 'svelte';
</script>

<section class="bg-white px-4 py-24 max-w-7xl mx-auto">
  <h1 class="text-4xl font-bold mb-8 text-center">Mis Proyectos</h1>
  <p class="text-gray-600 mb-16 text-lg text-center max-w-2xl mx-auto">
    Aquí encontrarás una recopilación de mis proyectos personales, profesionales y académicos.
  </p>

  <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">

    <!-- Pack&Track -->
    <a href="/proyectos/pack_and_track" class="block border rounded-2xl p-6 shadow-lg hover:scale-105 transition bg-white">
      <img src="/P&T_Naranja.svg" alt="Pack&Track" class="rounded-lg mb-4 h-48 w-full object-contain">
      <span class="bg-gray-100 text-gray-700 text-xs font-semibold px-2 py-0.5 rounded mb-2 inline-block">Proyecto Personal</span>
      <h3 class="text-2xl font-semibold mb-2">Pack&Track</h3>
      <p class="text-gray-600 mb-3">Sistema de seguimiento de paquetes con backend en Go y PostgreSQL, frontend en Svelte y despliegue cloud en Render, Neon y Vercel.</p>
      <div class="flex flex-wrap gap-2 mb-4">
        <span class="bg-sky-100 text-sky-800 text-xs font-medium px-2.5 py-0.5 rounded">Go</span>
        <span class="bg-indigo-100 text-indigo-800 text-xs font-medium px-2.5 py-0.5 rounded">PostgreSQL</span>
        <span class="bg-pink-100 text-pink-800 text-xs font-medium px-2.5 py-0.5 rounded">Svelte</span>
        <span class="bg-gray-200 text-gray-800 text-xs font-medium px-2.5 py-0.5 rounded">Git</span>
      </div>
      <span class="text-blue-600 hover:underline">Ver más →</span>
    </a>

    <!-- To-Do List -->
    <a href="#" target="_blank" rel="noopener noreferrer" class="block border rounded-2xl p-6 shadow-lg hover:scale-105 transition bg-white">
      <img src="/todolist.svg" alt="To-Do List App" class="rounded-lg mb-4 h-48 w-full object-contain">
      <span class="bg-gray-100 text-gray-700 text-xs font-semibold px-2 py-0.5 rounded mb-2 inline-block">Proyecto Personal</span>
      <h3 class="text-2xl font-semibold mb-2">To-Do List App</h3>
      <p class="text-gray-600 mb-3">App de tareas fullstack en desarrollo con Go, PostgreSQL y GraphQL, con frontend planeado en Svelte y API Gateway propio.</p>
      <div class="flex flex-wrap gap-2 mb-4">
        <span class="bg-sky-100 text-sky-800 text-xs font-medium px-2.5 py-0.5 rounded">Go</span>
        <span class="bg-indigo-100 text-indigo-800 text-xs font-medium px-2.5 py-0.5 rounded">PostgreSQL</span>
        <span class="bg-purple-100 text-purple-800 text-xs font-medium px-2.5 py-0.5 rounded">GraphQL</span>
        <span class="bg-pink-100 text-pink-800 text-xs font-medium px-2.5 py-0.5 rounded">Svelte</span>
      </div>
      <span class="text-blue-600 hover:underline">Ver más →</span>
    </a>

    <!-- Portafolio -->
    <a href="/proyectos/portafolio" class="block border rounded-2xl p-6 shadow-lg hover:scale-105 transition bg-white">
      <img src="/portafolio.png" alt="Portafolio Personal" class="rounded-lg mb-4 h-48 w-full object-cover">
      <h3 class="text-2xl font-semibold mb-2">Portafolio Personal</h3>
      <p class="text-gray-600 mb-3">Mi portafolio web minimalista, rápido y responsivo desarrollado con Svelte y Tailwind CSS, alojado en Vercel.</p>
      <div class="flex flex-wrap gap-2 mb-4">
        <span class="bg-pink-100 text-pink-800 text-xs font-medium px-2.5 py-0.5 rounded">Svelte</span>
        <span class="bg-blue-100 text-blue-800 text-xs font-medium px-2.5 py-0.5 rounded">Tailwind</span>
        <span class="bg-gray-100 text-gray-800 text-xs font-medium px-2.5 py-0.5 rounded">Vercel</span>
      </div>
      <span class="text-blue-600 hover:underline">Ver más →</span>
    </a>

    <!-- Facultad Ciencias -->
    <a href="/proyectos/pagina_web_facultad_de_ciencias" class="block border rounded-2xl p-6 shadow-lg hover:scale-105 transition bg-white">
      <img src="/facultad_ciencias.png" alt="Facultad Ciencias" class="rounded-lg mb-4 h-48 w-full object-cover">
      <h3 class="text-2xl font-semibold mb-2">Página Web Facultad de Ciencias - UNAL</h3>
      <p class="text-gray-600 mb-3">Sitio institucional desarrollado y desplegado con rediseño completo y migración de contenidos.</p>
      <div class="flex flex-wrap gap-2 mb-4">
        <span class="bg-orange-100 text-orange-800 text-xs font-medium px-2.5 py-0.5 rounded">HTML</span>
        <span class="bg-blue-100 text-blue-800 text-xs font-medium px-2.5 py-0.5 rounded">CSS</span>
        <span class="bg-green-100 text-green-800 text-xs font-medium px-2.5 py-0.5 rounded">WordPress</span>
        <span class="bg-gray-200 text-gray-800 text-xs font-medium px-2.5 py-0.5 rounded">Apache</span>
      </div>
      <span class="text-blue-600 hover:underline">Ver más →</span>
    </a>

    <!-- Conectify -->
    <a href="/proyectos/conectify" class="block border rounded-2xl p-6 shadow-lg hover:scale-105 transition bg-white">
      <img src="/conectify.png" alt="Conectify" class="rounded-lg mb-4 h-48 w-full object-contain">
      <span class="bg-gray-100 text-gray-700 text-xs font-semibold px-2 py-0.5 rounded mb-2 inline-block">Proyecto Académico</span>
      <h3 class="text-2xl font-semibold mb-2">Conectify</h3>
      <p class="text-gray-600 mb-3">API REST de red social de contactos rápidos con Go, Echo y despliegue en Docker. Proyecto académico 2023.</p>
      <div class="flex flex-wrap gap-2 mb-4">
        <span class="bg-sky-100 text-sky-800 text-xs font-medium px-2.5 py-0.5 rounded">Go</span>
        <span class="bg-purple-100 text-purple-800 text-xs font-medium px-2.5 py-0.5 rounded">Echo</span>
        <span class="bg-teal-100 text-teal-800 text-xs font-medium px-2.5 py-0.5 rounded">Docker</span>
      </div>
      <span class="text-blue-600 hover:underline">Ver más →</span>
    </a>

    <!-- GENDY -->
    <a href="/proyectos/gendy" class="block border rounded-2xl p-6 shadow-lg hover:scale-105 transition bg-white">
      <img src="/gendy.png" alt="GENDY" class="rounded-lg mb-4 h-48 w-full object-contain">
      <span class="bg-gray-100 text-gray-700 text-xs font-semibold px-2 py-0.5 rounded mb-2 inline-block">Proyecto Académico</span>
      <h3 class="text-2xl font-semibold mb-2">GENDY</h3>
      <p class="text-gray-600 mb-3">Sistema de generación de horarios en PHP con almacenamiento en MySQL y SQLite. Proyecto académico 2020.</p>
      <div class="flex flex-wrap gap-2 mb-4">
        <span class="bg-yellow-100 text-yellow-800 text-xs font-medium px-2.5 py-0.5 rounded">PHP</span>
        <span class="bg-indigo-100 text-indigo-800 text-xs font-medium px-2.5 py-0.5 rounded">MySQL</span>
        <span class="bg-gray-200 text-gray-800 text-xs font-medium px-2.5 py-0.5 rounded">SQLite</span>
      </div>
      <span class="text-blue-600 hover:underline">Ver más →</span>
    </a>

    <!-- ConectArte -->
    <a href="/proyectos/conectarte" class="block border rounded-2xl p-6 shadow-lg hover:scale-105 transition bg-white">
      <img src="/conectarte.png" alt="ConectArte" class="rounded-lg mb-4 h-48 w-full object-contain">
      <span class="bg-gray-100 text-gray-700 text-xs font-semibold px-2 py-0.5 rounded mb-2 inline-block">Proyecto Académico</span>
      <h3 class="text-2xl font-semibold mb-2">ConectArte</h3>
      <p class="text-gray-600 mb-3">Plataforma cultural web en Django con frontend en HTML y CSS. Proyecto académico 2023.</p>
      <div class="flex flex-wrap gap-2 mb-4">
        <span class="bg-green-100 text-green-800 text-xs font-medium px-2.5 py-0.5 rounded">Django</span>
        <span class="bg-orange-100 text-orange-800 text-xs font-medium px-2.5 py-0.5 rounded">HTML</span>
        <span class="bg-blue-100 text-blue-800 text-xs font-medium px-2.5 py-0.5 rounded">CSS</span>
      </div>
      <span class="text-blue-600 hover:underline">Ver más →</span>
    </a>

    <!-- CADUN -->
    <a href="/proyectos/cadun" class="block border rounded-2xl p-6 shadow-lg hover:scale-105 transition bg-white">
      <img src="/cadun.png" alt="CADUN" class="rounded-lg mb-4 h-48 w-full object-contain">
      <span class="bg-gray-100 text-gray-700 text-xs font-semibold px-2 py-0.5 rounded mb-2 inline-block">Proyecto Académico</span>
      <h3 class="text-2xl font-semibold mb-2">CADUN</h3>
      <p class="text-gray-600 mb-3">API de consulta de datos de usuarios universitarios en Go, proyecto académico 2024 con despliegue local en Docker.</p>
      <div class="flex flex-wrap gap-2 mb-4">
        <span class="bg-sky-100 text-sky-800 text-xs font-medium px-2.5 py-0.5 rounded">Go</span>
        <span class="bg-purple-100 text-purple-800 text-xs font-medium px-2.5 py-0.5 rounded">Echo</span>
        <span class="bg-teal-100 text-teal-800 text-xs font-medium px-2.5 py-0.5 rounded">Docker</span>
        <span class="bg-indigo-100 text-indigo-800 text-xs font-medium px-2.5 py-0.5 rounded">PostgreSQL</span>
      </div>
      <span class="text-blue-600 hover:underline">Ver más →</span>
    </a>

  </div>
</section>
