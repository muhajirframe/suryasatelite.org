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
        <a class="nav-item is-tab is-hidden-mobile is-active">Home</a>
        <a class="nav-item is-tab is-hidden-mobile">About</a>
        <nuxt-link to="/team" class="nav-item is-tab is-hidden-mobile">Team</nuxt-link>
        <a class="nav-item is-tab is-hidden-mobile">Donate</a>
      </div>

    </div>
  </nav>
</template>
