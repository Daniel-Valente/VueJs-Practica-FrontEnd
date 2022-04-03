<template>
  <div class="container">
    <hr>
    <h1><b>ORDENAR</b></h1>
  </div>
  <div class="container">
    <div class="card" style="background-color: #E0BBE4">
      <div class="card-body">
      </div>
    </div>
  </div>
  <br>
  <form>
    <div class="container">
      <div class="row">
        <div class="col-sm">
          <br>
            <h5> 
              <b>
                <hr>
                <div class="row">
                  <div class="col-sm" style="background-color: #FFDAC1;"></div>
                  <div class="col-sm">SELECCIONAR SABORES</div>
                  <div class="col-sm" style="background-color: #FFDAC1;"></div>
                </div>
                <hr>
              </b>
            </h5>
          <DifferentFlavor/>
        </div>
        <div class="col-sm">
          <br>
            <h5> 
              <b>
                <hr>
                <div class="row">
                  <div class="col-sm" style="background-color: #C7CEEA;"></div>
                  <div class="col-sm">SELECCIONAR ADORNOS</div>
                  <div class="col-sm" style="background-color: #C7CEEA;"></div>
                </div>
                <hr>
              </b>
            </h5>
          <DifferentOrnament/>
        </div>
      </div>
      <Form/>
      <br>
      <input class="btn" type="submit" value="Confirmar Pedido" style="background-color: #FF9AA2; color: #fff; font-weight: bold;">
    </div>
  </form>
</template>

<script>
import DifferentFlavor from "@/components/DifferentFlavor.vue";
import DifferentOrnament from "@/components/DifferentOrnament.vue";
import Form from "@/components/Form.vue";

export default {
  name: 'Order',
  components: {
    DifferentFlavor,
    DifferentOrnament,
    Form
  },
}
</script>