<template>
  <div id="About">
    <Navbar2/>
    <br><br><br><br><br>
    <img src="../assets/christine.png" class="rounded-circle">
    <br><br>
    <div id="name">Christine Park</div>
    <hr>
    <br>
    <div>
      <a href="https://www.instagram.com/jscpark/">
        <img src="../assets/instagram.svg" class="logo"> jscpark</img>
      </a>
    </div>
    <br>
    <div>
      <a href="https://www.vsco.co/jscpark">
        <img src="../assets/vsco.png" class="logo"> jscpark</img>
      </a>
    </div>
    <br><br><br><br>
  </div>
</template>
<script>
 import Navbar2 from './Navbar2'

export default {
  name: 'About',
  components: {
    Navbar2
  }
}
</script>
<style scoped>
  img {
    width: 200px;
    height: 200px;
  }
  
  hr {
    width: 50%;
  }

  #name {
    letter-spacing: 4px;
  }

  .logo {
    width: 30px;
    height: 30px;
    margin-right: 5px;
    margin-left: 5px;
  }

  a {
    color: black;
  }

  a:vistied {
    color: black;
  }


</style>
