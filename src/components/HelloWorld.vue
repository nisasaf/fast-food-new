<template>
  <h1>{{ msg }}</h1>

  <button type="button" class="rounded-full bg-indigo-500 px-4 py-2 text-white my-3 shadow-lg" @click="count++">count is: {{ count }}</button>
</template>

<script setup>
  import { ref } from 'vue'

  defineProps({
    msg: String
  })

  const count = ref(0)
</script>

<style scoped>
  a {
    color: #42b983;
  }
</style>
