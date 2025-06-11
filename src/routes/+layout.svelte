<script lang="ts">
  import '../app.css';
  import Navbar from '../lib/components/Navbar.svelte';
  import Footer from '../lib/components/Footer.svelte';

  const sections = [
    { name: 'Inicio', href: '/' },
    { name: 'Proyectos', href: '/proyectos' },
    { name: 'Servicios', href: '/servicios' },
  ];
</script>

<Navbar {sections} />

<div class="pt-20">
  <slot />
</div>

<Footer />
