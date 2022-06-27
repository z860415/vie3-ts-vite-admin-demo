<template>
  <div v-bind:style="style">
  demo string
  </div>
</template>

<script setup lang="ts">
type Style = {
  color: String,
  height: String
}

const style: Style = {
    color: "blue",
    height: "300px"
}

</script>

<style>
</style>
