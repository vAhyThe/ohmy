<style rel="stylesheet/scss" lang="sass">
  @import './index'
</style>

<template>
    <div class="Reference">
      <h2 class="Reference__title">Reference</h2>
      <div class="Reference__holder">
        <div class="Reference__item">
          <div class="Reference__item--logo">
            <dj-logo />
          </div>
          <h3 class="Reference__item--title">
            www.damejidlo.cz
          </h3>
          <div class="Reference__item--img">
            <img src="./image/damejidlo.png" height="289" width="467"/>
          </div>
        </div>

        <div class="Reference__item">
          <div class="Reference__item--logo">
            <balik-logo />
          </div>
          <h3 class="Reference__item--title">
            www.balikonos.cz
          </h3>
          <div class="Reference__item--img">
            <img src="./image/balikonos.png" height="289" width="467"/>
          </div>
        </div>

        <div class="Reference__item">
          <div class="Reference__item--logo">
            <zonky-logo />
          </div>
          <h3 class="Reference__item--title">
            www.zonky.cz
          </h3>
          <div class="Reference__item--img">
            <img src="./image/zonky.png" height="289" width="467"/>
          </div>
        </div>

        <div class="Reference__item">
          <div class="Reference__item--logo">
            <igglu-logo />
          </div>
          <h3 class="Reference__item--title">
            www.igluu.com
          </h3>
          <div class="Reference__item--img">
            <img src="./image/iggluu.png" height="289" width="467"/>
          </div>
        </div>
      </div>
      <div class="Reference__holder--small">
        <bmw />
        <o2 />
        <jaguar />
        <pandora />
      </div>
    </div>
</template>

<script>
import djLogo from './image/dj-logo.svg'
import balikLogo from './image/balik-logo.svg'
import zonkyLogo from './image/zonky-logo.svg'
import iggluLogo from './image/igluu-logo.svg'
import bmw from './image/bmw.svg'
import o2 from './image/o2.svg'
import jaguar from './image/jaguar.svg'
import pandora from './image/pandora.svg'

export default {
  name: 'Reference',

  components: {
    djLogo,
    balikLogo,
    zonkyLogo,
    iggluLogo,
    bmw,
    o2,
    jaguar,
    pandora
  }
}
</script>
