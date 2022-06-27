<template>
  <div @click="parent">
  <button @click.stop="clickTap">click</button>
  </div>
</template>

<script setup lang="ts">
const parent = () => {
    console.log('父級')
}

const   clickTap = () => {
    console.log('子級')
}

</script>

<style>
</style>
