<script setup>
defineProps({
  active: {
    type: Boolean,
    default: true,
  },
});
</script>

<template>
  <button
    type="button"
    :class="[
      'h-10 inline-flex justify-center px-4 py-2 text-sm font-medium  border border-transparent rounded-md focus:outline-none focus-visible:ring-2 focus-visible:ring-offset-2 neumorphism-shadow',
      active
        ? 'text-blue-900 bg-blue-100 hover:bg-blue-200  focus-visible:ring-blue-500 transition-all '
        : 'text-gray-400 bg-gray-100 focus-visible:ring-gray-500 cursor-default',
    ]"
  >
    <slot></slot>
  </button>
</template>

<style scoped></style>
