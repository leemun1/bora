<script setup>
defineProps({
  imageURL: {
    type: String,
    default: '',
  },
});
</script>

<template>
  <div
    class="w-80 h-80 rounded-md neumorphism-shadow flex justify-center items-center text-gray-500"
  >
    <div v-if="!imageURL">No image to display</div>
  </div>
</template>
