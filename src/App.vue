<template>
  <div id="app">
    <h1>Devices.css Demo</h1>
    <h2>iPhone X</h2>
    <IPhoneX/>
  </div>
</template>

<script>
import IPhoneX from './components/IPhoneX.vue'

export default {
  name: 'App',
  components: {
    IPhoneX
  }
}
</script>

<style>
@import './assets/devices.min.css';

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
