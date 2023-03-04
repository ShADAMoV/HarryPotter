<script setup>
import HNav from '@/features/HNav.vue';
import HLogo from '@/shared/HLogo.vue';
</script>

<template>
  <header class="h-header">
    <h-logo class="h-header__logo" />
    <h-nav />
  </header>
</template>

<style lang="scss" scoped>
.h-header {
  display: flex;
  align-items: center;
  height: 105px;
  background: #000000;
  box-shadow: 0 1px 2px rgba(0, 0, 0, 0.08);
  padding-left: 40px;
  padding-right: 40px;

  &__logo {
    margin-right: 50px;
  }
}
</style>