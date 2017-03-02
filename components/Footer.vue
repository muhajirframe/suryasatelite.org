<template>
  <footer class="footer">
    <div class="container">
      <div class="level">
        <div class="level-item">
          <social-media/>
        </div>
        <div class="level-item">
          <p>
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
  max-width: 100%;
}
@media (max-device-width: 1080px) {
  .footer>.container>.level {
    flex-direction: column;
  }
}
.level-item {
  padding-top: 0.2rem;
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
