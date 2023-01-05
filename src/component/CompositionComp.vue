<template>
  <div>
    <div>{{ num }}</div>
    <button @click="increaseNum">
      increase
    </button>
  </div>
</template>

<script setup>
import { ref } from 'vue'

const num = ref(0)

const increaseNum = () => {
  num.value++
}
</script>
