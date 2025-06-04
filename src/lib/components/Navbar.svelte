<script lang="ts">
  const scrollToSection = (id: string) => {
    document.getElementById(id)?.scrollIntoView({ behavior: 'smooth' });
  };
</script>

<nav class="fixed top-4 left-1/2 transform -translate-x-1/2 bg-[#0F172A] shadow-lg rounded-[30px] px-20 py-5 z-50">
  <div class="flex space-x-8">
    <a href="#hero" class="text-white hover:text-blue-400">Inicio</a>
    <a href="#proyectos" class="text-white hover:text-blue-400">Proyectos</a>
    <a href="#servicios" class="text-white hover:text-blue-400">Servicios</a>
    <a href="#sobremi" class="text-white hover:text-blue-400">Sobre mí</a>
  </div>
</nav>

<style>
  nav {
    backdrop-filter: blur(10px);
  }
</style>
