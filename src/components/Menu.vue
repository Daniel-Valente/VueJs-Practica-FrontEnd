<template>
  <div class="container">
    <hr>
    <h1><b>MENU</b></h1>
  </div>
  <div class="container">
    <div class="card" style="background-color: #E0BBE4">
      <div class="card-body">
      </div>
    </div>
  </div>
  <br>
  <div class="container"> 
    <div class="row">
      <div class="col-sm" style="background-color: #B6D8F2;">
      </div>
      <div class="col-sm">
        <div class="card" style="border: none;">
          <div id="carouselExampleDark" class="carousel carousel-dark slide" data-bs-ride="carousel">
            <div class="carousel-indicators">
              <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
              <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="1" aria-label="Slide 2"></button>
              <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="2" aria-label="Slide 3"></button>
            </div>
            <div class="carousel-inner">
              <div class="carousel-item active" data-bs-interval="10000">
                <img src="@/assets/Tres-Leches.jpg" class="d-block img-fluid" alt="..." width="100%" height="100%">
                <div class="carousel-caption d-none d-md-block">
                </div>
              </div>
              <div class="carousel-item" data-bs-interval="2000">
                <img src="@/assets/Pastel-de-queso.jpg" class="d-block img-fluid" alt="..." width="100%" height="100%">
                <div class="carousel-caption d-none d-md-block">
                </div>
              </div>
              <div class="carousel-item">
                <img src="@/assets/Vainilla.jpg" class="d-block img-fluid" alt="..." width="100%" height="100%">
                <div class="carousel-caption d-none d-md-block">
                </div>
              </div>
            </div>
            <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleDark" data-bs-slide="prev">
              <span class="carousel-control-prev-icon" aria-hidden="true"></span>
              <span class="visually-hidden">Previous</span>
            </button>
            <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleDark" data-bs-slide="next">
              <span class="carousel-control-next-icon" aria-hidden="true"></span>
              <span class="visually-hidden">Next</span>
            </button>
          </div>
        </div>
      </div>
      <div class="col-sm"  style="background-color: #B6D8F2;"></div>
    </div>
  </div>
  <Flavor/>
  <Ornament/>
</template>

<script>
import Flavor from "@/components/Flavor.vue";
import Ornament from "@/components/Ornament.vue";

export default {
  name: 'Menu',
  components: {
    Flavor,
    Ornament,
  },
}
</script>