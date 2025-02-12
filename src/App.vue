<script setup>
import { ref } from 'vue'

const count = ref(0)
</script>
<template>
  <p>{{ count }}</p>
  <div @click="count++">
    <button @click="$event.stopPropagation()">button</button>
  </div>
  <a href="https://vuejs.org" @click.prevent="$event.preventDefault()">Vue.js</a>
</template>
