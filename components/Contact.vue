<template>
  <section class="hero">
    <div class="hero-head">
      <div class="container">
        <h1 class="title section-title">Contact Us</h1>
      </div>
    </div>
    <div class="hero-body">
      <div class="container">
        <div class="columns is-multiline">
          <a v-for="item in contacts" class="column is-half">
            <span class="icon is-large">
              <img :src="`/${item.type}.svg`" width="100%">
            </span>
            <span class="subtitle">
              {{ item.value }}
            </span>
          </a>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped>
  .hero {
    /*background-color: #FAFAFA;*/
    background-color: #455A64;
  }
  .subtitle {
    position: relative;
    top: 0.8rem;
  }
  .title, .subtitle {
    color: #fff;
  }
</style>

<script>
export default {
  data: function () {
    return {
      contacts: [
        {
          type: 'instagram',
          value: 'suryasatelite1'
        },
        {
          type: 'twitter',
          value: '@suryasatelite1'
        },
        {
          type: 'email',
          value: 'contact@suryasatelite.org'
        },
        {
          type: 'phone',
          value: '+6285270403281'
        }
      ]
    }
  }
}
</script>
