<script>
  let name = 'Ainabkoi School of Agriculture';
</script>

<main>
  <h1>Welcome to {name}</h1>
  <p>Visit <a href="https://svelte.dev">svelte.dev</a> to learn how to build Svelte apps.</p>
</main>

<style>
  main {
    text-align: center;
    padding: 1em;
    max-width: 240px;
    margin: 0 auto;
  }

  h1 {
    color: #165a36;
    text-transform: uppercase;
    font-size: 4em;
    font-weight: 100;
  }

  @media (min-width: 640px) {
    main {
      max-width: none;
    }
  }
</style>
