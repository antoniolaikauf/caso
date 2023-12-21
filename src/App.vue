<script >
import Header from './components/ComponentHeader.vue'

import Main from  './components/ComponentMain.vue'

export default {
  components:{
    Header,
    Main
  }
}
</script>

<template>
  <Header />
  <Main />
</template>

<style lang="scss">
@use './style/general.scss' as *;
@use './style/partials/variable' as *;

.color{
  background-color: red;
}
</style>
