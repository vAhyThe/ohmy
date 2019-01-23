<style rel="stylesheet/scss" lang="sass">
  @import './index'
</style>

<template>
  <footer class="Footer">
    <img-logo class="Footer__background"/>
    <div class="Haystack">
      <div class="Haystack__holder">
        <div class="Haystack__ball__holder">
          <div class="Haystack__ball">
            <img-haystack />
          </div>
        </div>
        <div class="Haystack__shadow">
          <img-haystack-shadow />
        </div>
      </div>
    </div>
    <div class="Dinosaurus">
      <div class="Dinosaurus__holder">
        <img-dino />
      </div>
    </div>
  </footer>
</template>

<script>
import ImgLogo from './image/image.svg'
import ImgHaystack from './image/haystack.svg'
import ImgHaystackShadow from './image/shadow.svg'
import ImgDino from './image/dino.svg'
import ImgCar from './image/footer_vozidlo.svg'

export default {
  name: 'Footer',

  components: {
    ImgLogo,
    ImgHaystack,
    ImgHaystackShadow,
    ImgDino,
    ImgCar
  }
}
</script>
