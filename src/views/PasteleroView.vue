<template>
<br>
  <div class="container">
    <div class="card" style="background-color: #FFDFD3; border: none;"> <br><br> </div> <br>
    <div class="row ">
      <div class="col-sm">

        <div style="height: 100%;">
          <img src="@/assets/cakes-2-fondo.jpg" class="card-img-top img-fluid" alt="...">
        </div>

      </div>
      <div class="col-sm">

        <div class="card  text-center" style="height: 100%; background-color: #E0BBE4; border: none;">
          
        </div>

      </div>
      <div class="col-sm">

        <div style="height: 100%;">
          <img src="@/assets/Vainilla.jpg" class="card-img-top  img-fluid" alt="...">
        </div>

      </div>
    </div> <br>
    <div class="card" style="background-color: #FFDFD3; border: none;"> <br><br> </div> <br>
    
   <div class="container"> 
      <div class="row">
        <div class="col-sm" style="background-color: #96F7D2;">
        </div>
        <div class="col-sm">
          <div class="card" style="border: none;">
            <div id="carouselExampleDark" class="carousel carousel-dark slide" data-bs-ride="carousel">
              <div class="carousel-indicators">
                <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
                <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="1" aria-label="Slide 2"></button>
                <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="2" aria-label="Slide 3"></button>
                <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="3" aria-label="Slide 4"></button>
                <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="4" aria-label="Slide 5"></button>
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
                <div class="carousel-item" data-bs-interval="2000">
                  <img src="@/assets/Chocolate.jpg" class="d-block img-fluid" alt="..." width="100%" height="100%">
                  <div class="carousel-caption d-none d-md-block">
                  </div>
                </div>
                <div class="carousel-item" data-bs-interval="2000">
                  <img src="@/assets/Vainilla.jpg" class="d-block img-fluid" alt="..." width="100%" height="100%">
                  <div class="carousel-caption d-none d-md-block">
                  </div>
                </div>
                <div class="carousel-item">
                  <img src="@/assets/Coco-limón.jpg" class="d-block img-fluid" alt="..." width="100%" height="100%">
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
      <div class="col-sm"  style="background-color: #96F7D2;"></div>
    </div>
   </div> <br>
  <div class="card" style="background-color: #FFDFD3; border: none;"> <br><br> </div> <br>
  <AmountFlavors/>
  <AmountOrnaments/>
  </div>
</template>

<script>
import AmountFlavors from "@/components/AmountFlavors.vue";
import AmountOrnaments from "@/components/AmountOrnaments.vue";
import CustomerOrders from "@/components/CustomerOrders.vue";

export default {
  name: 'PasteleroView',
  components: {
      AmountFlavors,
      AmountOrnaments,
      CustomerOrders
  }
}
</script>
