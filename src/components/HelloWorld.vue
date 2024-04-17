<script setup lang="ts">
const props = defineProps<{
  msg: string
}>()
</script>

<template>
  <div class="wrapper">
    <span>{{ props.msg }}</span>
  </div>
</template>

<style scoped></style>
