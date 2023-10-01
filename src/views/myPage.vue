<template>
  <v-card :title="page.page" />
  <myComponent />
</template>

<script lang="ts" setup>
  const page = defineProps(["page"])
  console.log(page)
  import myComponent from '@/components/myComponent.vue'
</script>
