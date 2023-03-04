<script setup>
import HNavItem from '@/shared/HNavItem.vue';
</script>

<template>
  <div class="h-nav">
    <HNavItem
      title="Главная"
      href="#"
    />
    <HNavItem
      title="Персонажи"
      href="#"
    />
  </div>
</template>

<style lang="scss" scoped>
.h-nav {
  display: flex;
  column-gap: 30px;
}
</style>