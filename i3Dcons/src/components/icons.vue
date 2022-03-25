<template>
  <div class="iconShowCase">
      <Icon/>
      <Icon/>
      <Icon/>
      <Icon/>
      <Icon/>

      <Icon/>
      <Icon/>
      <Icon/>
      <Icon/>
      <Icon/>

      <Icon/>
      <Icon/>
      <Icon/>
      <Icon/>
      <Icon/>

      <Icon/>
      <Icon/>
      <Icon/>
      <Icon/>
      <Icon/>
  </div>
</template>

<script>
import Icon from './icon.vue'
export default {
    components: {
    Icon
  }
}
</script>

<style scoped>
.iconShowCase {
  width: calc(100% - 100px);
  padding: 0 50px;
  display: grid;
  grid-template-columns:20% 20% 20% 20% 20%;
  justify-items: center;
  row-gap: 50px;
}
</style>