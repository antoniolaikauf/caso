<script >
import HelloWorld from './components/HelloWorld.vue'

export default {
  components:{
    HelloWorld
  }
}
</script>

<template>
  <HelloWorld />
</template>

<style lang="scss">
@use './style/general.scss' as *;
@use './style/partials/variable' as *;

.color{
  background-color: red;
}
</style>
