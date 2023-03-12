<script setup>
defineProps({
  title: {
    type: String,
    required: true,
  },
  href: {
    type: String,
    required: true,
  },
});
</script>

<template>
  <router-link
    class="h-nav-item"
    :to="`${href}`"
  >
    {{ title }}
  </router-link>
</template>

<style lang="scss" scoped>
.h-nav-item {
  font-size: 20px;
  line-height: 26px;
  color: #B09A81;
  text-decoration: none;
}
</style>