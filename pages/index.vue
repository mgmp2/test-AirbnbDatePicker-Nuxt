<template lang="pug">
  section.container
    div
      airbnb-date-picker
      h1.title test-airbnb-date
      h2.subtitle
        | My classy Nuxt.js project
      .links
        a(href="https://nuxtjs.org/" target="_blank" class="button--green") Documentation
        a(href="https://github.com/nuxt/nuxt.js" target="_blank" class="button--grey") GitHub
</template>

<script>
import AirbnbDatePicker from '~/components/AirbnbDatePicker.vue'

export default {
  data () {
    return {}
  },
  components: {
    AirbnbDatePicker
  }
}
</script>
