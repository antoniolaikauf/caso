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
  <!-- componente header -->
  <Header />
  <!-- componente main -->
  <Main />
  <!-- componente footer -->
  <Footer/>
</template>

<style lang="scss">
@use './style/general.scss' as *;
@use './style/partials/variable' as *;
// cartteristiche di h3 del progetto 
h3{
  color: $color_title;
}
</style>

<!-- non usare i nomi come i tag del html 
 -->