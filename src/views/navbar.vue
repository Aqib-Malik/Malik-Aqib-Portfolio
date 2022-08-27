<template>
  <div>
    <!-- NAVBAR-->
    <nav
    id="Navv"
      class="
        navbar navbar-expand-sm
        py-3
        navbar-dark
        shadow-sm
        fixed-top
      "
      style="background-color: #E9BA3C;"
        
    >
      <div class="container">
        <a href="#" class="navbar-brand">
          <!-- Logo Image -->
          <img
            src="../assets/img/aqib6.jpg"
            width="45"
            alt=""
            class="d-inline-block align-middle mr-2"
          />
          <!-- Logo Text -->
          <span class="text-uppercase font-weight-bold"
            >Malik Aqib Mehmood</span
          >
        </a>
        <!-- <button type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation" class="navbar-toggler"><span class="navbar-toggler-icon"></span></button>

    <div id="navbarSupportedContent" class="collapse navbar-collapse">
      <ul class="navbar-nav ml-auto">
        <li class="nav-item active"><a href="#" class="nav-link">Home <span class="sr-only">(current)</span></a></li>
        <li class="nav-item"><a href="#about" class="nav-link">About</a></li>
        <li class="nav-item"><a href="#portfolio" class="nav-link">Portfolio</a></li>
      </ul>
    </div> -->
        <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

        <b-collapse id="nav-collapse" is-nav>
          <b-navbar-nav>
            <ul class="navbar-nav ml-auto nav-pills">
              <li class="nav-item active">
                <a href="#" class="nav-link"
                  >Home <span class="sr-only">(current)</span></a
                >
              </li>
              <li class="nav-item active">
                <a href="#about" class="nav-link">About</a>
              </li>
              <li class="nav-item active">
                <a href="#portfolio" class="nav-link">Portfolio</a>
              </li>
              <li class="nav-item active">
                <a href="#skill" class="nav-link">Skills</a>
              </li>
              <li class="nav-item active">
                <a href="#contact" class="nav-link">Contact</a>
              </li>
            </ul>
          </b-navbar-nav>

          <!-- Right aligned nav items -->
          <b-navbar-nav class="ml-auto"> </b-navbar-nav>
        </b-collapse>
      </div>
    </nav>
  </div>
</template>
<script>
export default {
  name: "navbar",
};
</script>
<style scoped>

img {
  
  border-radius: 50%;
  
}
#nav li :hover {
  background-color: #87CEEB;
}
 /* #E9BA3C;" */
</style>