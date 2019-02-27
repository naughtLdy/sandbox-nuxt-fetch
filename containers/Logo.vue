<template>
  <LogoContainer />
</template>

<script>
import LogoContainer from '~/containers/logo/index.vue'

export default {
  components: {
    LogoContainer
  },
  fetch() {
    console.log('container directory fetch event')
  }
}
</script>
