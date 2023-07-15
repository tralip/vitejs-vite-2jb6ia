<script setup lang="ts">
import HelloWorld from './components/HelloWorld.vue'
import TheExperience from './components/TheExperience.vue'
import ThreeDProject from './components/ThreeDProject.vue'

</script>

<template>
  <div>
    <p>zone pour ThreeDProject.vue composant</p>
    <p>+- Début dans App.vue</p>
      <ThreeDProject msg="(Vite/Vue/TS) TresJS" />
    <p>+- Fin dans App.vue</p>
    
  </div>
  <div>
   <p>zone pour TheExperience.vue</p>
   <TheExperience/>
  </div>
  <p>(la suite est la démo de départ)</p>
 <!-- <div>
    <a href="https://vitejs.dev" target="_blank">
      <img src="/vite.svg" class="logo" alt="Vite logo" />
    </a>
    <a href="https://vuejs.org/" target="_blank">
      <img src="./assets/vue.svg" class="logo vue" alt="Vue logo" />
    </a>
  </div>
  <HelloWorld msg="Vite + Vue" /> -->
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
