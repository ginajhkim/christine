<template>
  <div id="home">
    <Navbar />
    <img src="../assets/quote.gif" id="gif">
    <div class="collage">
      <div class="row">
        <div class="col-sm first-col">
          <img src="../assets/8.png" class="images">
        </div>
        <div class="col-sm second-col">
          <img src="../assets/9.png" class="images">
        </div>
      </div>
      <div class="row">
        <div class="col-sm first-col">
          <img src="../assets/5.png" class="images">
        </div>
        <div class="col-sm second-col">
          <img src="../assets/6.png" class="images">
        </div>
      </div>
    </div>
    <b-button variant="custom" class="more"><router-link to="Gallery" class="more-button" >﹀</router-link></b-button>
    
  </div>
</template>

<script>
import Navbar from './Navbar'

export default {
  name: 'home',
  components: {
    Navbar
  }
}
</script>

<style scoped>
#home {
 overflow-x: hidden;
}
#gif {
  width: 100%;
}

.images {
  width: 100%;
  height: auto;
}

.first-col {
  padding-top: 5vh;
  padding-left: 8vh;
}

.second-col {
  padding-top: 5vh;
  padding-right: 8vh;
}

.collage {
  padding-bottom: 5vh;
}

.more-button {
  color: black;
  font-size: 15pt;
}
.more {
  padding-top: 0;
}


@media only screen and (max-width: 575px) {
  .first-col {
    padding: 0;
  }
  .second-col {
    padding: 0;
  }
  .collage {
    padding: 30px;
    padding-bottom: 0;
  }
  .col-sm {
    padding-bottom: 20px;
  }
}

</style>
