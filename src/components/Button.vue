<script setup></script>

<template>
  <button
    type="button"
    class="h-10 inline-flex justify-center px-4 py-2 text-sm font-medium text-blue-900 bg-blue-100 border border-transparent rounded-md hover:bg-blue-200 focus:outline-none focus-visible:ring-2 focus-visible:ring-offset-2 focus-visible:ring-blue-500 transition-all neumorphism-shadow"
    @click="someMethod"
  >
    <slot></slot>
  </button>
</template>

<style scoped></style>
