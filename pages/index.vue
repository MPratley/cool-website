<template>
  <section class="container">
    <div>
      <div class="name-container">
        <h1 class="first">
          Marcus
        </h1>
        <h1 class="second">
          James
        </h1>
        <h1 class="third">
          Pratley
        </h1>
      </div>
      <h2 class="subtitle">
        is a developer, this is his website
      </h2>
      <div class="links">
        <NuxtLink
          to="/about"
          class="button--grey"
        >
          Yes
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
  color: var(--theme-color-accent);
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>

<style scoped>
.name-container {
  /* position: relative; */
  font-size: calc(10vw);
  font-family: Verdana, serif;
  margin: 0;
}

.first {
  text-align: left;
  position: absolute;
  color: palevioletred;
  top: 0px;
  left: 0px;
}

.second {
  position: absolute;
  color: navajowhite;
  mix-blend-mode: color-burn;
  top: calc(5vw);
  left: calc(5vw);
}

.third {
  position: absolute;
  top: calc(10vw);
  left: calc(10vw);
  color: darkturquoise;
  mix-blend-mode: color-burn;
}
</style>
