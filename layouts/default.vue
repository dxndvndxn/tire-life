<template>
  <div id="app">
    <HeaderBar />
    <Nuxt />
  </div>
</template>

<script>
import HeaderBar from '../components/common/layout/header'
export default {
  name: 'Default',
  components: {
    HeaderBar
  }
}
</script>

<style scoped>

</style>
