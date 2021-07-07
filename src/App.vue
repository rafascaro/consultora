<template>
  <body class="bg-red-500">
    <div class="flex h-screen">
      <div class="m-auto p-8 max-w-md md:max-w-2xl bg-transparent rounded">
        <h1 class="uppercase tracking-wide">Consultora</h1>
        <h2 class="uppercase tracking-wide">Loica</h2>
      </div>
    </div>
  </body>
</template>

<script setup>
import { defineProps, reactive } from 'vue'

defineProps({
  msg: String
})

const state = reactive({ count: 0 })
</script>