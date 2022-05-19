<script lang="ts">
  import Header from '$lib/Header.svelte'
  import '../app.css'
</script>

<div>
  <Header />

  <main>
    <slot />
  </main>

  <footer>
    <p>Made in Ithaca, NY</p>
  </footer>
</div>

<style>
  div {
    display: flex;
    flex-direction: column;
    padding: 3rem 2rem;
    width: fit-content;
    max-width: 640px;
    margin: 0 auto;
  }

  main {
    flex: 1;
    display: flex;
    flex-direction: column;
  }

  footer {
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 2rem;
  }
</style>
