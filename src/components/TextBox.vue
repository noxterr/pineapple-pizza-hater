<script setup lang="ts">
  import { ref } from 'vue'

  defineProps<{
    title: string
    description: string
  }>()

  const count = ref(0)
</script>

<template>
  <div className="text-wrap">
    <h1 className="title">{{ title }}</h1>
    <p className="description"> {{ description }} </p>
  </div>
</template>

<style>
</style>
