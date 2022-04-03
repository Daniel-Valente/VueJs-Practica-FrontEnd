<template>
  <div class="home">

    <br>
    <Presentation/>
    <br> <br>
    <div class="container">
      <div class="card" style="background-color: #B5EAD7;">
        <div class="card-body h3">
          POSTRES DISEÑADOS A TU GUSTO Y ESTILO
        </div>
      </div>
    </div>

    <div class="container">
      <br>
      <div class="btn-group" role="group" aria-label="Basic example">
        <button type="button" class="btn btn-secondary" @click="scrollInto('contact')">Conóceme</button>
        <button type="button" class="btn btn-secondary">&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp</button>
        <button type="button" class="btn btn-secondary" @click="scrollInto('menu')">Menú</button>
      </div>
    </div>

    <br>
    
    <div class="container">
      <div class="row">
        <div class="col-sm">
          <img src="@/assets/panaderos.jpg" class="img-fluid" width="100%">
        </div>
        <div class="col-sm">
          <img src="@/assets/donus.jpg" class="img-fluid"  width="100%">
        </div>
      </div>
    </div>

    <br>
    <div id="menu"><Menu/></div>
    <div id="order"><Order/></div>
    <div id="contact"><Contact/></div>

    <div class="card" style="background-color: #fff3eb;">
      <div class="card-body">
        <h6>
          <small>©2022 Creado por KM Repostería </small>
        </h6>
      </div>
    </div>
  </div>
</template>

<script>
import Presentation from "@/components/Presentation.vue";
import Menu from "@/components/Menu.vue";
import Order from "@/components/Order.vue";
import Contact from "@/components/Contact.vue";

export default {
  name: 'HomeView',
  components: {
    Presentation,
    Menu,
    Order,
    Contact
  },
  methods: {
    scrollInto(elementId) {
      const section = document.querySelector(`#${elementId}`);
      section.scrollIntoView({
        behavior: 'smooth'
      });
    }
  }
}
</script>

<style scoped>
.col-sm-aux {
  position: relative;
}

.col-sm-aux .btn-creado{
  position: absolute;
  left: 60%;
  bottom: 10%;
}
.col-sm-aux .btn-creado-2{
  position: absolute;
  left: 70%;
  bottom: 10%;
}
</style>