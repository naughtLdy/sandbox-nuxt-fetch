<template>
  <LogoContainer />
</template>

<script>
import LogoContainer from '~/pages/containers/index.vue'

export default {
  components: {
    LogoContainer
  },
  fetch() {
    console.log('pages directory fetch event')
  }
}
</script>
