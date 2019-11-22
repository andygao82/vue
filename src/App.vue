<template>
  <div id="app">
    <img src="./assets/logo.png">
    <hr>
      <button class="btn btn-primary">Confirm</button>
      <button class="btn btn-success">Use</button>
      <button class="btn btn-danger">Alert</button>
    <hr>
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
@import './assets/custom.scss';
</style>
