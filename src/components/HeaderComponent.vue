<template>
  <header class="header">
    <nav class="header__nav">
      <router-link class="header__item" to="/"><img src="@/assets/home.svg" alt="home"></router-link>
      <router-link class="header__item" to="/settings"><img src="@/assets/gear.svg" alt="gear"></router-link>
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
  &__item {
    color: #000;
  }

  &__nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
}
</style>
