<template>
  <div class="p-2 grid grid-cols-4 gap-2 h-full">
    <div
      class="bg-slate-50 h-full flex items-center justify-center hover:bg-fuchsia-200 cursor-pointer"
      v-for="(item, index) in gridList"
      :key="index"
    >
      敬请期待
    </div>
  </div>
</template>
<script lang="ts" setup>
import { ref } from 'vue'
let gridList = ref<number[]>([1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12])
</script>
<style lang="scss" scoped></style>
