<script>
import SiteHeader from './components/SiteHeader.vue'
import SiteMain from './components/SiteMain.vue'

export default {
  name: 'App',
  components: {
    SiteHeader,
    SiteMain
  },
  data() {
    return {

    }
  }
}

</script>

<template>
  <site-header></site-header>
  <site-main></site-main>
</template>

<style>

</style>