<template>
  <div class="container">
    <div class="row ">
      <div class="col-sm">

        <div style="height: 100%;">
          <img src="@/assets/cake-fodo.jpg" class="card-img-top img-fluid" alt="...">
        </div>

      </div>
      <div class="col-sm">

        <div class="card  text-center" style="height: 100%; background-color: #FEC8D8;">
          <div class="card-body">
            <figure>
              <blockquote class="blockquote">
                <p class="h3"> <br><br> Diseño de pasteles para todo momentos</p>
              </blockquote>
            </figure>
            <a class="btn btn-light" @click="scrollInto('order')">Hacer un pedido</a>
          </div>
        </div>

      </div>
      <div class="col-sm">

        <div style="height: 100%;">
          <img src="@/assets/cakes-fondo.jpg" class="card-img-top  img-fluid" alt="...">
        </div>

      </div>
    </div>
  </div>
</template>

<script>

export default {
  name: 'Presentation',
  components: {
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