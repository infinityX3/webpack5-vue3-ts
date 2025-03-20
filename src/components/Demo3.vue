<template>
  我是Demo3组件
  <button @click="handleClick">Click</button>
</template>
<script>
import { subtract } from '@/assets/utils/index.js';
export default {
  methods: {
    handleClick() {
      subtract(5, 3)
    },
  },
};
</script>

<style scoped></style>