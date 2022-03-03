<template>
  <div id="app">
     <SiteHeader />

    <router-view/>

    <SiteFooter />
  </div>
</template>

<script>
import SiteHeader from './components/SiteHeader.vue'
import SiteFooter from './components/SiteFooter.vue'

export default {
  name: 'App',
  components: {
    SiteHeader,
    SiteFooter
  }
}
</script>

<style lang="scss">
@import "../node_modules/bootstrap/scss/bootstrap.scss";

@import "./assets/scss/variables.scss";
@import "./assets/scss/common.scss";
</style>
