<template>
  <div class="level">
    <div v-for="contact in contacts" class="level-item">
    <span class="icon">
          <img :src="`/${contact.type}.svg`" alt="instagram">
    </span>
   <span class="social-media-text">{{ contact.value }}</span>
    </div>
   <!--<span class="social-media-text">{{contact.value}}</span>-->
  </div>
</template>

<style scoped>
.social-media-text {
  padding-left: 0.5rem;
  padding-right: 2rem;
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
