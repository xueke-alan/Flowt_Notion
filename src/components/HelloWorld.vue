<script setup lang="ts">
import { ref } from 'vue'

defineProps<{ msg: string }>()

const count = ref(0)
</script>

<template>
  <button type="button" @click="count++">拉取</button>
  <button type="button" @click="count++">查找</button>
  <button type="button" @click="count++">删除</button>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
