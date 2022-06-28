<template>
<div>
{{message}}
</div>
</template>

<script setup lang="ts">
import { reactive } from 'vue';

type O = {
  list: number[]
}

let message = reactive<O>({
  list:[]
})

setTimeout(() => {
  message.list = [1,2,3,4,5,6]
}, 1000)

</script>

<style>
</style>
