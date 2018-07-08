<style rel="stylesheet/scss" lang="sass">
  @import './index'
</style>

<template>
  <header class="Header">
    <img-logo />
  </header>
</template>

<script>
import ImgLogo from './image/logo.svg'

export default {
  name: 'Header',

  components: {
    ImgLogo
  }
}
</script>
