<template>
  <footer class="footer">
    <div class="container">
      <div class="level">
        <div class="level-left">
          <social-media/>
        </div>
        <div class="level-right">
        <p class="">
          Designed by <a href="https://hellomuhajir.com">Muhammad Muhajir</a>
        </p>
        </div>
      </div>

    </div>
</footer>
</template>

<style scoped>
.social-media-text {
  padding-left: 0.5rem;
}
.footer {
  padding: 2rem 1.5rem;
  color: #fff;
  font-size: 1.1rem;
  background-color: #2c3e50;
}
a:hover {
  color: #00d1b2;
}
</style>

<script>
import SocialMedia from '~components/SocialMedia.vue'
export default {
  components: {
    SocialMedia
  }
}
</script>
