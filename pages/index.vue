<template>
  <section class="container">
    <div>
        <h1>code. @codingsh</h1>
        <p>I'm a specialist blockchain developer, I'm cooking all the time, these are my main <a href="https://twitter.com/codingsh/status/1347788648243200000?s=20uF">dishes</a>. I surf the blockchain in a spaceship.</p>
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
