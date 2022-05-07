<template>
  <nuxt-page></nuxt-page>

  <landing-footer></landing-footer>
</template>


<script setup>
import LandingFooter from '@/components/landing/Footer'

useHead({
  htmlAttrs: {
    class: 'scroll-smooth'
  }
})
</script>
