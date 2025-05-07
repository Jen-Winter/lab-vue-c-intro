
<template>
    <div class="hero">
    <img width=129px height=129px src="/Users/jenniferw/Documents/Jennifer-Repository-Ironhack/vue/lab-vue-c-intro/vue-project/src/images/Vue_logo.png" alt="Vue Logo">
    <h1> Welcome to Vue.js</h1>
    <h2> Become a coding ninja with the fastest-growing JavaScript framework</h2>
    <button class=btn-1>Awesome!</button>
    </div>
</template>

<style scoped>

.hero {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  height: 312px;
  width: 600px;
  color: #2B2F30;
  width: 456px;
  height: 299px;
  gap: 1rem;
  margin: 4rem;
}

.btn-1 {
  background-color: #34495E;
  color: white;
  width: 121px;
  height: 31px;
  border-radius: 13px;
  font-weight: bold;
    font-size: 14px;
    line-height: 20px;
}

h2 {
  text-align: center;
}

</style>