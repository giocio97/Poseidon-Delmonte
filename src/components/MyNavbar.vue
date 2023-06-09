<template>
  <div id="jumbo-bg" class="container-fluid">
    <nav class="navbar navbar-dark navbar-expand-lg">
      <div class="container-fluid text-white">
        <a class="navbar-brand" href="#"><img class="logo" src="../assets/logoP.png" alt="logo"></a>

        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent"
          aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav me-auto mb-2 mb-lg-0">
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="#">Landing</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Theme</a>
            </li>

            <li class="nav-item">
              <a class="nav-link" href="# ">Pages</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Blog</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Risorse</a>
            </li>

            <li class="nav-item">
              <a class="nav-link" href="#">Email</a>
            </li>
          </ul>

          <div class="d-flex">
            <a class="me-5" href="#"><i class="fa-solid fa-globe" style="color:#4DFFDF"></i></a>
            <button class="btn btn-primary" type="submit">Custom Call to Action</button>
          </div>
        </div>
      </div>
    </nav>

    <div class="container-fluid jumbo">
      <div class="row d-flex">
        <div class="col-lg-2 col-12">
          <span id="minuti">34</span>
          <span>Minuti di lettura</span>
        </div>
        <div class="col-lg-10 col-12 d-flex flex-column align-items-center align-items-lg-start">
          <h1 class="text-center text-lg-start">Pillar Page Title</h1>
          <span class="text-center text-lg-start">Lorem ipsum dolor sit amet consectetur adipisicing elit.</span>
        </div>
      </div>
    </div>
  </div>
</template>
  
<script>
export default {
  name: 'MyNavbar',

}
</script>
  
  <!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
* {
  color: white;
}

#jumbo-bg {
  background-image: url('../assets/jumbo.jpeg');
  height: 100%;

  .logo {
    width: 200px;
    height: 150px;
  }

  .jumbo {
    margin-top: 500px;
    padding-bottom: 100px;

    #minuti {
      padding: 5px;
      color: #4DFFDF;
      border: 2px solid #4DFFDF;
      border-radius: 50%;
      margin: 5px;
    }

    
  }

}
</style>
  