<template>
  <div>
    <bar/>
    <nuxt/>
    <my-footer/>
  </div>
</template>

<script>
import MyFooter from '~components/Footer.vue'
import Bar from '~components/Bar.vue'

export default {
  components: {
    MyFooter,
    Bar
  }
}
</script>
