<template>
  <div id="app">
    <Head/>
    <TopArea/>
    <Icons/>
  </div>
</template>

<script>
import Head from './components/head.vue'
import TopArea from './components/topArea.vue'
import Icons from './components/icons.vue'

export default {
  name: 'App',
  components: {
    Head,
    TopArea,
    Icons
  }
}
</script>

<style>
#app {
  background: #E5E5E5;
}
</style>
