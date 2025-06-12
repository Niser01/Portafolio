<script lang="ts">
  export let sections: { name: string; href: string }[] = [];

  let menuOpen = false;
  const toggleMenu = () => menuOpen = !menuOpen;
</script>

<nav class="bg-[#0F172A] py-6 fixed top-0 left-0 w-full z-50 shadow">
  <div class="w-full max-w-7xl mx-auto px-6 flex justify-between items-center">
    
    <!-- Logo -->
    <a href="/" class="text-white text-2xl font-bold">Portafolio</a>

    <!-- Botón hamburguesa (móvil) -->
    <button
      class="lg:hidden text-white focus:outline-none"
      on:click={toggleMenu}
      aria-label="Abrir menú de navegación">
      <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
          d="M4 6h16M4 12h16M4 18h16" />
      </svg>
    </button>

    <!-- Navegación normal (desktop) -->
    <div class="hidden lg:flex flex-1 justify-center space-x-8">
      {#each sections as section}
        <a href={section.href} class="text-gray-300 hover:text-white transition">{section.name}</a>
      {/each}
    </div>

    <!-- Botón de contacto -->
    <div class="hidden lg:block">
      <a href="/contacto" class="bg-blue-600 hover:bg-blue-700 text-white px-5 py-2 rounded-full transition">
        Contacto
      </a>
    </div>
  </div>
</nav>

<!-- Menú desplegable (móvil) -->
{#if menuOpen}
  <div class="lg:hidden bg-[#0F172A] pt-4 pb-6 space-y-4 fixed top-[64px] left-0 w-full z-50 transition-all duration-300">
    <div class="px-6">
      {#each sections as section}
        <a
          href={section.href}
          class="block text-gray-300 hover:text-white text-lg transition"
          on:click={() => menuOpen = false}>
          {section.name}
        </a>
      {/each}

      <a
        href="/contacto"
        class="block bg-blue-600 hover:bg-blue-700 text-white text-center py-3 rounded-full transition mt-4"
        on:click={() => menuOpen = false}>
        Contacto
      </a>
    </div>
  </div>
{/if}

