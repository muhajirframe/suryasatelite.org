<template>
  <nav class="nav has-shadow is-large">
    <div class="container">
      <div class="nav-left">
        <nuxt-link to="/" class="nav-item">
          Logo Surya Satelite
        </nuxt-link>
      </div>

      <span class="nav-toggle" :class="{ 'is-active': dropdown }" @click="dropdown = !dropdown">
      <span></span>
      <span></span>
      <span></span>
      </span>

     <div class="nav-right nav-menu" :class="{ 'is-active': dropdown }">
      <nuxt-link to="/" active-class="is-active" class="nav-item is-tab" exact>Home</nuxt-link>
      <nuxt-link to="/about" active-class="is-active" class="nav-item is-tab">About</nuxt-link>
      <nuxt-link to="/team" active-class="is-active" class="nav-item is-tab">Team</nuxt-link>
      <nuxt-link to="/donate" active-class="is-active" class="nav-item is-tab">Donate</nuxt-link>
    </div> 

    </div>
  </nav>
</template>

<style scoped>
.nav {
  min-height: 4.5rem;
}
.nav-toggle {
  height: 100%;
}
</style>

<script>
export default {
  data: function () {
    return {
      dropdown: false
    }
  }
}
</script>
