<template>
  <div>
    <page-header />
    <hero />
  </div>
</template>

<script>
import Hero from '@/components/Hero/index'
import PageHeader from '@/components/Header/index'

export default {
  name: 'HomePage',

  components: {
    Hero,
    PageHeader
  }
}
</script>
