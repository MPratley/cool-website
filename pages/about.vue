<template>
  <section class="container">
    <div>
      <h1 class="title">
        cool website
      </h1>
      <h2 class="subtitle">
        A cool and good website that makes people go &#34;wow&#34; and &#34;ooo&#34;
      </h2>
      <div class="links">
        <NuxtLink to="/" class="button--grey">
          Home
        </NuxtLink>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  layout: 'default'
}
</script>

<style scoped>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 400;
  font-size: 4em;
  color: #35495e;
  text-align: center;
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
</style>
