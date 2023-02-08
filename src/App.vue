<template>
  <div class="container">
    <HeaderComponent />
    <router-view />
  </div>
</template>

<script lang="ts">
import HeaderComponent from './components/HeaderComponent.vue';
export default {
  components: {
    HeaderComponent
  }
}
</script>

<style lang="scss">
.container {
  width: 500px;
  height: 500px;
  border: 1px solid #000;
  position: fixed;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  padding: 20px;
}
</style>
