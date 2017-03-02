<template>
  <div>
    <big-header/>
    <donate/>
  </div>
</template>

<script>
import BigHeader from '~components/BigHeader.vue'
import Donate from '~components/Donate.vue'
export default {
  components: {
    BigHeader,
    Donate
  }
}
</script>

<style>
.section-title {
  padding-top: 2rem;
}
@media only screen and (max-width: 768px) {
  .section-title {
    padding-left: 2rem;
  }
}
</style>
