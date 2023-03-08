<script>
  import '../global.css';
  import Nav from '../inc/Nav.svelte';
  import Footer from '../inc/Footer.svelte';
</script>

<Nav />

<main>
  <slot />
</main>

<Footer />
