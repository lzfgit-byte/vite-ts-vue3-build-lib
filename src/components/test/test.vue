<template>
  <h1>你好{{ a }}</h1>
</template>

<script setup lang="ts">
  import { ref } from 'vue';
  import type { strType } from '@/components/test/test';

  const a = ref<strType>('0');
</script>

<style scoped lang="less"></style>
