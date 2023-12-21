<script >
import Header from './components/ComponentHeader.vue'

import Main from  './components/ComponentMain.vue'

import Footer from './components/ComponentFooter.vue'

export default {
  components:{
    Header,
    Main,
    Footer
  }
}
</script>

<template>
  <Header />
  <Main />
  <Footer/>
</template>

<style lang="scss">
@use './style/general.scss' as *;
@use './style/partials/variable' as *;

h3{
  color: $color_title;
}
</style>
