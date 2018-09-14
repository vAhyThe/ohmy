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
