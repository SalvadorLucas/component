<template>
  <div id="app">
    <demo></demo>
  </div>
</template>
<script>
import './assets/libs/myLib.umd.js'
export default {
  props:{

  },
  name: 'myLib',
  components: {
    demo: myLib
  }
}
</script>
<style>
</style>
