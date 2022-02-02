<script setup>
import Button from '../../components/Button.vue';

function onClickMainButton() {
  console.log('yo!');
}
</script>

<template>
  <div class="grow flex items-center justify-center">
    <Button @click="onClickMainButton">Click me!</Button>
  </div>
</template>

<style scoped></style>
