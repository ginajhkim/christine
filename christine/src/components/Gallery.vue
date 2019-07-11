<template>
  <div class="gallery">
    <Navbar2/>
    <b-container class="collage">
      <div class="container">
        <div class="row">
      <b-col sm="6" md="3" lg="3" class="first-col">
          <b-button v-b-modal.modal-1 variant="custom">
            <img src="../assets/gallery/g1.png" class="images">
          </b-button>
          <b-modal id="modal-1" hide-footer>
            <img src="../assets/gallery/g1.png">
          </b-modal>
          
          <b-button v-b-modal.modal-2 variant="custom">
            <img src="../assets/gallery/g7.png" class="images">
          </b-button>
          <b-modal id="modal-2" hide-footer>
            <img src="../assets/gallery/g7.png">
          </b-modal>

          <b-button v-b-modal.modal-3 variant="custom">
            <img src="../assets/gallery/g9.png" class="images">
          </b-button>
          <b-modal id="modal-3" hide-footer>
            <img src="../assets/gallery/g9.png">
          </b-modal>
          
          <b-button v-b-modal.modal-4 variant="custom">
            <img src="../assets/gallery/g13.png" class="images">
          </b-button>
          <b-modal id="modal-4" hide-footer>
            <img src="../assets/gallery/g13.png">
          </b-modal>
      </b-col>
    
      <b-col sm="6" md="3" lg="3" class="col-sm second-col">
        <b-button v-b-modal.modal-5 variant="custom">
          <img src="../assets/gallery/g6.png" class="images">
        </b-button>
        <b-modal id="modal-5" hide-footer>
          <img src="../assets/gallery/g6.png">
        </b-modal>

        <b-button v-b-modal.modal-6 variant="custom">
          <img src="../assets/gallery/g5.png" class="images">
        </b-button>
        <b-modal id="modal-6" hide-footer>
          <img src="../assets/gallery/g5.png">
        </b-modal>

        <b-button v-b-modal.modal-7 variant="custom">
          <img src="../assets/gallery/g10.png" class="images">
        </b-button>
        <b-modal id="modal-7" hide-footer>
          <img src="../assets/gallery/g10.png">
        </b-modal>

        <b-button v-b-modal.modal-8 variant="custom">
          <img src="../assets/gallery/g11.png" class="images">
        </b-button>
        <b-modal id="modal-8" hide-footer>
          <img src="../assets/gallery/g11.png">
        </b-modal>
      </b-col>

      <b-col sm="6" md="3" lg="3" class="first-col">
        <b-button v-b-modal.modal-9 variant="custom">
          <img src="../assets/gallery/g3.png" class="images">
        </b-button>
        <b-modal id="modal-9" hide-footer>
          <img src="../assets/gallery/g3.png">
        </b-modal>

        <b-button v-b-modal.modal-10 variant="custom">
          <img src="../assets/gallery/g2.png" class="images">
        </b-button>
        <b-modal id="modal-10" hide-footer>
          <img src="../assets/gallery/g2.png">
        </b-modal>

        <b-button v-b-modal.modal-11 variant="custom">
          <img src="../assets/gallery/g15.png" class="images">
        </b-button>
        <b-modal id="modal-11" hide-footer>
          <img src="../assets/gallery/g15.png">
        </b-modal>
      </b-col>
      <b-col sm="6" md="3" lg="3" class="first-col">
        <b-button v-b-modal.modal-12 variant="custom">
          <img src="../assets/gallery/g4.png" class="images">
        </b-button>
        <b-modal id="modal-12" hide-footer>
          <img src="../assets/gallery/g4.png">
        </b-modal>

        <b-button v-b-modal.modal-13 variant="custom">
          <img src="../assets/gallery/g8.png" class="images">
        </b-button>
        <b-modal id="modal-13" hide-footer>
          <img src="../assets/gallery/g8.png">
        </b-modal>

        <b-button v-b-modal.modal-14 variant="custom">
          <img src="../assets/gallery/g16.png" class="images">
        </b-button>
        <b-modal id="modal-14" hide-footer>
          <img src="../assets/gallery/g16.png">
        </b-modal>
      </b-col>
      </div>
      </div>
      </b-container>
    </div>
</template>

<script>
import Navbar2 from './Navbar2'

export default {
  name: 'Gallery',
  components: {
    Navbar2
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  img {
    width: 100%;
  }

  .gallery {
    padding: 20px;
    margin-top: 40px;
  }
  .images {
    padding-top: 20px;
  }

  .btn {
    padding: 0;
  }

  @media only screen and (max-width: 575px) {
    
  }
</style>
