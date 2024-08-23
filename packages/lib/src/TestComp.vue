<script setup lang="ts">
defineProps<{
  msg: number
  msg2: number
}>()
</script>

<template>
  <div>
    {{ msg }}
  </div>
</template>
