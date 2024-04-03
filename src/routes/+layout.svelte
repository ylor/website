<script>
  import "$lib/styles/reset.css";

  import Header from "../lib/partials/Header.svelte";
  import Footer from "../lib/partials/Footer.svelte";
</script>

<Header />

<main>
  <slot />
</main>

<Footer />

<style>
  :global(html) {
    background: #111;
    color: #ccc;
  }
</style>
