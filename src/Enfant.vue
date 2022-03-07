<template>
  <h1>Hello</h1>
  <h2 v-bind="attrs">Hello 2</h2>
</template>

<script setup lang="ts">
import { useAttrs } from 'vue';

const attrs = useAttrs();
</script>

<style scoped lang="scss">
.container {
  background-color: red;
}
</style>
