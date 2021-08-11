<template>
  <div class="flex h-screen">
    <div class="m-auto">
      <figure>
        <img src="../src/assets/logo.svg" class="h-24"/> 
      </figure> 
    </div>
  </div>
</template>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Inter:wght@100;300;400;700&display=swap');
</style>
<script setup>
  import { defineProps, reactive } from 'vue'
  defineProps({
    msg: String
  })
  const state = reactive({ count: 0 })
</script>