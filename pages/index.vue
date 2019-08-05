<template>
  <section class="container">
    <div>
      <h1 class="title">
        Marcus Pratley <br> is ostensibly a developer
      </h1>
      <h2 class="subtitle">
        This is his website
      </h2>
      <div class="links">
        <NuxtLink
          to="/about"
          class="button--green"
        >
          About
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
