<template>
  <section class="hero is-large">
    <div class="hero-body">
      <div class="container has-text-centered">
        <h1 class="title is-1">
          {{ error.statusCode }}
        </h1>
        <h2 class="subtitle is-2">
          {{ error.message }}
        </h2>
        <nuxt-link class="button is-warning is-outlined is-large" to="/" v-if="error.statusCode === 404">
          Homepage
        </nuxt-link>
      </div>
    </div>
  </section>
</template>
<style scoped>
.hero {
  background-color: #e74c3c;
}
.title, .subtitle {
  color: #fff;
}
.button:hover.is-warning.is-large {
  color: #e74c3c
}
</style>
<script>
export default {
  props: ['error']
}
</script>
