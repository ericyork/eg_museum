<script>
  import '$lib/global.css';
  import Nav from '$lib/Nav.svelte';
  import Aside from '$lib/Aside.svelte';
  import Footer from '$lib/Footer.svelte';
</script>

<Nav />

<main class="container">
  <article>
    <slot />
  </article>
  <aside>
    <Aside />
  </aside>
</main>

<Footer />
