<template>
  <section class="hero is-primary is-fullheight">
    <div class="hero-body">
      <div class="level container">
        <div class="level-item">
          <figure class="image">
            <img  class="round" src="../assets/img/satelite.png">
          </figure>
        </div>
        <div class="level-item">
          <div class="tagline">
            <h1 class="title is-2">Surya Satelite 1</h1>
            <br />
            <h2 class="subtitle is-5">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quaerat, nihil.</h2>
            <br />
            <nuxt-link to="/about">
              <button class="button is-outlined is-warning is-large">
                What is Surya Satelite 1?
              </button>
            </nuxt-link>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped>
.round {
  border-radius: 50%;
}
.tagline {
  text-align: center;
  padding-top: 20px;
}
.button:hover.is-warning {
  color: #00d1b2;
}
</style>
