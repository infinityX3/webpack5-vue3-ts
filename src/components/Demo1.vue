<template>
  我是Demo1组件
  <button @click="handleClick" class="test-ak">Click</button>
</template>
<script>
import { add } from '@/assets/utils/index.js';

export default {
  methods: {
    handleClick() {
      add(1, 2)
    },
  },
};
</script>

<style scoped>
.test-ak { 
  font-size: 12px;
  content: '哈哈哈';
}
</style>