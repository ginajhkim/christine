<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<script>
import Mainpage from './components/Mainpage'
import Navbar from './components/Navbar'
export default {
  name: 'App'
}
</script>

<style>
  html,
  body {
    background: #FFFAF4;
  }
</style>
