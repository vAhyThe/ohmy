<template>
  <div>
    <div class="Grid">
      <div class="Grid__inner">
        <page-header />
        <hero />
        <planet-part />
        <about />
        <reference />
      </div>
    </div>
    <page-footer />
    <div class="Grid Grid--nopadding">
      <div class="Grid__inner">
        <div class="Footer__copy">
          <div class="Footer__copy--left">© Tomáš Váhala 2019</div>
          <div class="Footer__copy--right">Design by Michal Hosnedl</div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Hero from '@/components/Hero/index'
import PageHeader from '@/components/Header/index'
import PageFooter from '@/components/Footer/index'
import planetPart from '@/components/planetPart/index'
import About from '@/components/About/index'
import Reference from '@/components/Reference/index'

export default {
  name: 'HomePage',

  components: {
    Hero,
    PageHeader,
    PageFooter,
    planetPart,
    About,
    Reference
  }
}
</script>
