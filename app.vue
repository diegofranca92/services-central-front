<template>
  <div>
    <!-- <primary-layout></primary-layout> -->
    <!-- <acavm-page></acavm-page> -->
    <NuxtPage />
  </div>
</template>
<script>
// import PrimaryLayout from './src/layouts/PrimaryLayout'
// import AcavmPage from './src/acavm/aca'
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
    // AcavmPage
    // PrimaryLayout
  }
}
</script>
