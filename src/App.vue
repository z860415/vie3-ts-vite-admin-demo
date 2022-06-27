<template>
  <div v-show="flag" v-html="message"></div>
</template>

<script setup lang="ts">
const message: string = "<section> demo </section>"
const flag: boolean = false

</script>

<style>
</style>
