<script setup lang="ts">
import { ref } from 'vue'

defineProps<{ msg: string }>()

const count = ref(0)
</script>

<template>
  <p>+-- Début ThreeDProject.vue</p>
  <h1>{{ msg }}</h1>

 <!-- <div class="card">
    <button type="button" @click="count++">count is {{ count }}</button>

  </div> -->

  <p>+-- Fin ThreeDProject.vue</p>

</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
