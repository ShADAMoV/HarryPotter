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
  <a
    class="h-nav-item"
    :href="`${href}`"
  >
    {{ title }}
  </a>
</template>

<style lang="scss" scoped>
.h-nav-item {
  font-size: 20px;
  line-height: 26px;
  color: #B09A81;
}
</style>