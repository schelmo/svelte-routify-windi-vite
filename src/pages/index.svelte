<header class="windi-py-12 windi-text-4xl windi-text-center">
  Application Starter Template
  <img src="/favicon.png" alt="Reepolee" class="windi-py-4 windi-mx-auto" />
</header>

<main>
  <div class="font-bold">Classes without prefix will still be generated</div>

  <p>A starter template for Svelte Application, uses Routify file-based router, WindiCSS to compile TailwindCSS and Vite.</p>

  <p>
    <a href="https://svelte.dev">Svelte</a><br />
    <a href="https://routify.dev">Routify</a><br />
    <a href="https://vitejs.dev">Vite</a><br />
    <a href="https://windicss.org/">WindiCSS</a><br />
  </p>

  <p>
    Kudos to all the respective authors, special thanks to <a href="https://github.com/jakobrosenberg">@jakobrosenberg</a> and
    <a href="https://github.com/dominikg">@dominikg.</a>
  </p>

  <p>
    <a href="/md">Markdown page</a>
  </p>


  
  <p>
    <a href="/fails">Have a look at 404</a>
  </p>

  <p>
    <a href="/axios-post">Axios example</a>
  </p>

  <h2>Should be on green and bold (global style). On blue for XL screen.</h2>
</main>

<style>
  main {
    @apply windi-p-8 windi-text-xl;
  }
  p {
    @apply windi-my-4;
  }
  /* you can still use @apply without prefix */
  a {
    @apply text-reepolee-500 font-bold;
  }
</style>
