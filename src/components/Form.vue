<template>
  <div class="container">
    <br>
      <h5> 
        <b>
          <hr>
          <div class="row">
            <div class="col-sm" style="background-color: #9AC8EB;"></div>
            <div class="col-sm">FINALIZAR PEDIDO</div>
            <div class="col-sm" style="background-color: #9AC8EB;"></div>
          </div>
          <hr>
        </b>
      </h5>
    <br>
    <div class="row">
      <div class="col-sm">
        <div class="input-group">
          <span class="input-group-text">Nombre y Apellido</span>
          <input type="text" aria-label="First name" class="form-control" id="nombre">
          <input type="text" aria-label="Last name" class="form-control" id="apellido">
        </div>
        <br>
      </div>
      <div class="col-sm">
        <div class="input-group">
          <span class="input-group-text">Correo electrónico</span>
          <input type="email" class="form-control" id="correo" placeholder="name@example.com">
        </div>
      </div>
    </div>
    <br>
    <div class="row">
      <div class="col-sm">
        <div class="input-group">
          <span class="input-group-text">Teléfono</span>
          <input type="number" class="form-control" id="telefono">
        </div>
        <br>
      </div>
      <div class="col-sm"></div>
    </div>
    <div class="input-group">
      <span class="input-group-text">Descripción General del Pastel</span>
      <textarea class="form-control" id="description" rows="3"></textarea>
    </div>
  </div>
</template>
<script>

export default {
  name: 'Form',
  components: {
  },
}
</script>