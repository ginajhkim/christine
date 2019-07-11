<template>
<nav id="nav" v-on="mounted()" class="navbar navbar-expand-sm fixed-top navbar-dark">
    <div class="container">
        <a class="navbar-brand">
          <router-link to="/">
          <img src="../assets/logo_transparent1.png">
          </router-link>
        </a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbar1" aria-controls="navbar1" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbar1">
            <ul class="navbar-nav ml-auto mt-2 mt-lg-0">
                <li class="nav-item active">
                  <router-link class="nav-link" to="Gallery">GALLERY</router-link>
                </li>
                <li class="nav-item active">
                    <router-link class="nav-link" to="About">ABOUT</router-link>
                </li>
            </ul>
        </div>
    </div>
</nav>
</template>

<script>
export default {
  methods: {
    mounted () {
      document.onreadystatechange = () => {
         if (document.readyState === 'complete') {
          document.getElementById('nav').style.opacity = 1
        }
      }
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  #nav {
    opacity: 0;
    transition:2s;
    width: 100%;
  }
  
  .navbar-brand img {
    width: 80px;
    height: 40px;
  }

  .navbar-brand {
    margin: 0;
  }

</style>
