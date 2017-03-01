<template>
  <div>
    <big-header/>
    <about/>
    <donate/>
    <contact/>
  </div>
</template>

<script>
import BigHeader from '~components/BigHeader.vue'
import About from '~components/About.vue'
import Donate from '~components/Donate.vue'
import Contact from '~components/Contact.vue'
export default {
  components: {
    BigHeader,
    About,
    Donate,
    Contact
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
