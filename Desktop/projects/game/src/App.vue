<template>
  <div id="app">
    <navbars />
    <router-view/>
  </div>
</template>

<script>
import navbars from "./components/navbars.vue"
export default {
  components:{
    navbars
  }
}
</script>
<style lang="scss">
</style>
