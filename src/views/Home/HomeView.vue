<script setup>
import { PhotographIcon, DownloadIcon } from '@heroicons/vue/outline';

import Button from '../../components/Button.vue';
import PostProcessingPreview from '../../components/PostProcessingPreview.vue';

function onClickUpload() {}

function onClickMainButton() {
  console.log('yo!');
}
function onClickDownload() {}
</script>

<template>
  <div class="grow flex flex-col items-center justify-center">
    <PostProcessingPreview />
    <div class="w-80 mt-6 flex">
      <Button class="w-16" @click="onClickUpload">
        <PhotographIcon class="w-5 h-5" />
      </Button>
      <Button :active="false" class="grow mx-4" @click="onClickMainButton">Click me!</Button>
      <Button :active="false" class="w-16" @click="onClickDownload">
        <DownloadIcon class="w-5 h-5" />
      </Button>
    </div>
  </div>
</template>

<style scoped></style>
