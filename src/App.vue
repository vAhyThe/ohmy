<style rel="stylesheet/scss" lang="sass">
  @import '../node_modules/normalize.css/normalize.css'
  @import './assets/styles/variables'
  @import './assets/styles/base'
  @import './assets/styles/grid'
</style>

<template>
  <div id="app">
    <div class="Holder">
      <router-view/>
    </div>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>
