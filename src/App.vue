<template>
<div>
  <button @click="changeMessage">change</button>
  <div>
    {{ message }}
  </div>
</div>
</template>

<script setup lang="ts">
import { ref, Ref } from 'vue'

let message: Ref<string> = ref("demo_message")
const changeMessage = () => {
    message.value = "changeMessage"
}

</script>

<style>
</style>
