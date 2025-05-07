<template>
  <div class="quality-container">
    <div class="quality-card">
      <img src="/Users/jenniferw/Documents/Jennifer-Repository-Ironhack/vue/lab-vue-c-intro/vue-project/src/images/USP-1.png" alt="icon" />
      <h3>Performant</h3>
      <p>
        Truly reactive, compiler-optimized rendering system that rarely requires manual
        optimization.
      </p>
    </div>
    <div class="quality-card">
      <img src="/Users/jenniferw/Documents/Jennifer-Repository-Ironhack/vue/lab-vue-c-intro/vue-project/src/images/USP-2.png" alt="icon" />
      <h3>Approachable</h3>
      <p>
        Builds on top of standard HTML, CSS and JavaScript with intuitive API and world-class
        documentation.
      </p>
    </div>
    <div class="quality-card">
      <img src="/Users/jenniferw/Documents/Jennifer-Repository-Ironhack/vue/lab-vue-c-intro/vue-project/src/images/USP-3.png" alt="icon" />
      <h3>Versatile</h3>
      <p>
        A rich, incrementally adoptable ecosystem that scales between a library and a full-featured
        framework.
      </p>
    </div>
  </div>
</template>

<style scoped>
.quality-container {
  display: flex;
  justify-content: space-evenly;
  background-color: #39B983;
  height: 312px;
  width: 600px;
  padding: 1rem;
  align-items: center
}

.quality-card {
    display: flex;
    flex-direction: column;
    align-items: center;
    color: black;
    width: 200px;
    padding: 2rem
}

.quality-card img {
  width: 50px;
  height: 50px;
}

p {
  font-size: 12px;
  line-height: 17px;
  letter-spacing: 0.1px;
  text-align: center;
}

h3 {
  font-size: 16px;
  line-height: 95px;
  letter-spacing: 0.1px;
  font-weight: 700;
}
</style>
