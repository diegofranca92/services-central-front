<template>
  <div>
    <primary-layout></primary-layout>
  </div>
</template>
<script>
import PrimaryLayout from './src/layouts/PrimaryLayout'
import { onMounted } from 'vue'
import {
  initAccordions,
  initCarousels,
  initCollapses,
  initDials,
  initDismisses,
  initDrawers,
  initDropdowns,
  initModals,
  initPopovers,
  initTabs,
  initTooltips
} from 'flowbite'

onMounted(() => {
  initAccordions()
  initCarousels()
  initCollapses()
  initDials()
  initDismisses()
  initDrawers()
  initDropdowns()
  initModals()
  initPopovers()
  initTabs()
  initTooltips()
})

export default {
  components: {
    PrimaryLayout
  }
}
</script>
