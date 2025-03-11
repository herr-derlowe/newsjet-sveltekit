<script>
  let name = $state("World");
  const NAMES = ["World", "James", "Igor", "Philemon", "Cornelius"];
  function changeName() {
    name = NAMES[Math.floor(Math.random() * NAMES.length)];
  }
</script>

<svelte:head>
  <title>Home</title>
</svelte:head>

<h1>Welcome to SvelteKit</h1>
<p>Hello {name}, this is your first SvelteKit app!</p>
<button onclick={changeName} class="button is-primary my-3">Change name</button>
<br />
<p>
  Visit <a href="https://svelte.dev/docs/kit">svelte.dev/docs/kit</a> to read the
  documentation
</p>

<section class="section">
  <div class="container has-text-centered">
    <h1 class="title">Hello World</h1>
    <p class="subtitle">
      My first website with <strong>Bulma</strong>!
    </p>
  </div>
</section>