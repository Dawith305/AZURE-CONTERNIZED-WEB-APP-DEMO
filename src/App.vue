<template>
    <div id="app">
      <div id="main" class="has-text-centered">
        <h1 class="title is-1">Greetings :)</h1>
        <h1 class="subtitle is-5 mt-4">Here is a demo of Containerized Web App using Azure App Service</h1>
      </div>
      <vue-particles
        color="#dedede"
        :particleOpacity="0.7"
        :particlesNumber="80"
        shapeType="circle"
        :particleSize="4"
        linesColor="#dedede"
        :linesWidth="1"
        :lineLinked="true"
        :lineOpacity="0.4"
        :linesDistance="150"
        :moveSpeed="3"
        :hoverEffect="true"
        hoverMode="grab"
        :clickEffect="true"
        clickMode="push"
      >
      </vue-particles>
    </div>
 </template>

<script>
export default {
  name: 'App'
}
</script>

<style>
html, body, #app {
    height: 100%;
}

#app {
  position: relative;
  background-image: url('./assets/image/bgimage2.jpg');
  background-size: cover;
}

#main {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translateY(-50%) translateX(-50%);
}

h1 {
  color: #fdebeb !important;
  text-shadow: 5px 5px 0px #000000;
  font-family: 'Dosis', sans-serif;
}
</style>
