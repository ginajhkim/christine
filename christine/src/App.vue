<template>
  <div id="app">
    <transition name="moveInUp">
      <keep-alive>
        <router-view/>
      </keep-alive>
    </transition>
  <hr>
  <footer>
    <div>Copyright © 2019 Gina Kim All rights reserved.</div>
    <div>Icons made by <a href="https://www.freepik.com/" title="Freepik">Freepik</a> from <a href="https://www.flaticon.com/"                 title="Flaticon">www.flaticon.com</a> is licensed by <a href="http://creativecommons.org/licenses/by/3.0/"                 title="Creative Commons BY 3.0" target="_blank">CC 3.0 BY</a></div>
  </footer>
  </div>
</template>

<script>
import Home from './components/Home'
import Navbar from './components/Navbar'

export default {
  name: 'App',
  components: {
    Home,

  }
}
</script>

<style scoped>
  #app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
  }
  .moveInUp-enter-active {
    animation: fadeIn 1s ease-in;
  }
  @keyframes fadeIn {
    0% {
      opacity: 0.5;
    }
    50% {
      opacity: 0.8;
    }
    100% {
      opacity: 1;
    }
  }
  a {
    color: gray;
  }
  hr {
    width: 70%
  }

  footer {
    color: gray;
  }
</style>
