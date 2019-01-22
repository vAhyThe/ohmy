<style rel="stylesheet/scss" lang="sass">
  @import './index'
</style>

<template>
  <div class="Planet__holder">
    <img-planet />
    <div class="Planet__holder--item"/>
  </div>
</template>

<script>
import imgPlanet from './image/planet.svg'

export default {
  name: 'planet',

  components: {
    imgPlanet
  }
}
</script>
