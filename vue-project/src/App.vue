<template>
  <div id="app">
    <Navigation />
    <Hero />
    <QualityComponent />
  </div>
</template>

<script>
export default {
  components: {
    Hero,
    QualityComponent,
    Navigation,
  },
  name: 'App',
}
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
  width: 600px;
  height: 803px;
  margin: 0;
  padding: 0;
  align-items: center;
}
</style>
