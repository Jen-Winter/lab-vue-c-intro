<template>
  <div id="app">
    <Navigation />
    <Hero />
    <QualityComponent />
  </div>
</template>

<script setup>

import Navigation from './components/Navigation.vue'
import Hero from './components/Hero.vue'
import QualityComponent from './components/QualityComponent.vue'
</script>

<style scoped>
#app {
  display: flex;
  flex-direction: column;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  background-color: white;
  margin: 0;
  padding: 0;
  align-items: center;
}
</style>
