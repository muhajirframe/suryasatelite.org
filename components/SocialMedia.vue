<template>
  <div class="level">
    <div v-for="contact in contacts" class="level-item">
      <span class="icon">
          <img :src="`/${contact.type}.svg`" alt="instagram">
      </span>
      <span class="social-media-text">
        <a :href="contact.link">
          {{ contact.value }}
        </a>
      </span>
    </div>
  </div>
</template>

<style scoped>
.social-media-text {
  padding-left: 0.5rem;
  padding-right: 2rem;
}
a {
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
            value: 'suryasatelite1',
            link: 'https://instagram.com/suryasatelite1'
          },
          {
            type: 'twitter',
            value: '@suryasatelite1',
            link: 'https://twitter.com/suryasatelite1'
          },
          {
            type: 'email',
            value: 'contact@suryasatelite.org',
            link: 'mailto:contact@suryasatelite.org'
          },
          {
            type: 'phone',
            value: '+6285270403281',
            link: 'tel:085270403281'
          }
        ]
      }
    }
  }
</script>
