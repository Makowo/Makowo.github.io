<template>
  <div class="flex justify-center flex-col items-center h-screen">
    <h1>{{"Error: " + error.statusCode}}</h1>
    <h1>{{error.statusMessage}}</h1>
    <button class="btn" @click="handleError">Return to Homepage</button>
  </div>
</template>

<script setup>
const props = defineProps({
  error: Object
})

const handleError = () => clearError({ redirect: '/' })
</script>
