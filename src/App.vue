<template>
  <Enfant class="container" @click="handler" />
</template>

<script setup lang="ts">
import { ref } from 'vue';
import Modal from './Modal.vue';

function handler() {
  console.log('clic !');
}
</script>

<style scoped lang="scss">
.container {
  background-color: blue;
}
</style>
