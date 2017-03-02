<template>
  <nav class="nav has-shadow is-large">
    <div class="container">
      <div class="nav-left">
        <nuxt-link to="/" class="nav-item">
          Logo Surya Satelite
        </nuxt-link>
      </div>

      <span class="nav-toggle">
      <span></span>
      <span></span>
      <span></span>
      </span>
      
      <div class="nav-right nav-menu">
        <nuxt-link to="/" class="nav-item is-tab is-hidden-mobile is-active">Home</nuxt-link>
        <nuxt-link to="/about" class="nav-item is-tab is-hidden-mobile">About</nuxt-link>
        <nuxt-link to="/team" class="nav-item is-tab is-hidden-mobile">Team</nuxt-link>
        <nuxt-link to="/donate" class="nav-item is-tab is-hidden-mobile">Donate</nuxt-link>
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

