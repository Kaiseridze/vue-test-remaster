<template>
  <header class="header">
    <nav class="header__nav">
      <router-link to="/">Home</router-link>
      <router-link to="/settings">Settings</router-link>
    </nav>
  </header>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'HeaderComponent',
});
</script>

<style scoped lang="scss">
.header {
  font-family: 'Poppins', sans-serif;

  &__nav {
    display: flex;
    justify-content: space-between;
  }
}
</style>
