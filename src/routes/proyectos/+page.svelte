<script>
  import { onMount } from 'svelte';
</script>

<section class="bg-white px-4 py-24 max-w-7xl mx-auto">
  <h1 class="text-4xl font-bold mb-8 text-center">Mis Proyectos</h1>
  <p class="text-gray-600 mb-16 text-lg text-center max-w-2xl mx-auto">Aquí encontrarás una recopilación de mis proyectos personales, profesionales y académicos.</p>

  <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
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

    <!-- Aquí más proyectos futuros -->
     
  </div>
</section>
