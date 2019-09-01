<template>
  <div id="navbar">
    <nav class="navbar navbar-expand-lg navbar-light">
      <a class="navbar-brand" href="#"></a>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav navbar-center">
            <div class="d-flex flex-row justify-content-center">
              <div class="p-2">
                <li class="nav-item">
                <a class="nav-link" href="#">PROJECTS<span class="sr-only">(current)</span></a>
                </li>
              </div>
              <div class="p-2">
                <li class="nav-item">
                  <a class="nav-link" href="#">RESUME</a>
                </li>
              </div>
              <div class="p-2">
                <li class="nav-item">
                  <a class="nav-link" href="#">ABOUT</a>
                </li>
              </div>
              <div class="p-2">
                <li class="nav-item">
                  <a class="nav-link" href="#">CONTACT</a>
                </li>
              </div>
            </div>
          </ul>
      </div>
    </nav>
    </div>

</template>

<script>
export default {
  name: 'navbar'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

.navbar{
  background-color: #FFFAF4;
}

.navbar-nav {
  float: none;
  margin: 0 auto;
  display: block;
  text-align: center;
}

.navbar-toggler{
  float: right;
}
</style>
