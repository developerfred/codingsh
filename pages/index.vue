<template>
  <section class="container">
    <div>
      <h1 class="title">
        codingsh | @codingsh
      </h1>
      <h2 class="subtitle">
        developer notes
      </h2>
      <div class="links">
        <a
          href="https://twitter.com/codingsh"
          target="_blank"
          class="button--green">Twitter</a>
        <a
          href="https://github.com/developerfred"
          target="_blank"
          class="button--grey">GitHub</a>
        <a
          href="https://instagram.com/codingshxyz"
          target="_blank"
          class="button--grey">Intagram</a>
      </div>
    </div>
  </section>
</template>

<style>
.container {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; /* 1 */
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}

@media (max-width: 600px) {
  .title {
    font-size: 21px;
  }
  .subtitle {
    font-size: 20px;
  }
  .links {
    display: none;
  }
}
</style>

