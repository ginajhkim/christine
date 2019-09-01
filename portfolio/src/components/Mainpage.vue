<template>
  <div id="main">
    <Navbar />
    <div class="container">
        <div id="logo-div" v-on="mounted()">
          <img id="logo" src="../assets/logo1.png">
        </div>
    </div>
    <hr id="line" v-on="mounted()">
    <div class="container" v-on="mounted()">
      <button type="button" class="btn" id="project-btn">VIEW PROJECTS</button>
    </div>
  </div>
</template>

<script>
import Navbar from './Navbar'

export default {
  methods: {
    mounted () {
      document.onreadystatechange = () => {
        if (document.readyState === 'complete') {
          document.getElementById('logo-div').style.opacity = 1
          document.getElementById('line').style.opacity = 1
          document.getElementById('project-btn').style.opacity = 3
        }
      }
    }
  },
  name: 'mainpage',
  components: {
    Navbar
  }
}

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .container {
    text-align: center;
    overflow: hidden;
  }

  #line {
    margin-top: 0;
    width: 70%;
    opacity: 0;
    transition: 6s;
  }

  #logo {
    margin-top: 10%;
    margin-bottom: 2%;
  }

  #logo-div {
    opacity: 0;
    transition: 4s;
  }

  #project-btn {
    color: #858585;
    opacity: 0;
    transition: 10s;
  }
</style>
