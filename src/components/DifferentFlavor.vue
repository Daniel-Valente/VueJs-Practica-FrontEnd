<template>
  <div class="container">
    <em>Puedes seleccionar más de un sabor para tu pastel:</em> <br> <br>
    <select class="form-select"  size="12" aria-label="select" multiple id="flavor[]">
      <option value="1">Chocolate</option>
      <option value="2">Coco Limón</option>
      <option value="3">Limón</option>
      <option value="4">Napoleón</option>
      <option value="5">Pastel de Queso</option>
      <option value="6">Red Velvet</option>
      <option value="7">Tiramisú</option>
      <option value="8">Tres Leches</option>
      <option value="9">Vainilla</option>
      <option value="10">Zanahoría</option>
      <option value="11">Café con Nuez</option>
      <option value="12">Fresa</option>
    </select>
  </div>
</template>
<script>

export default {
  name: 'DifferentFlavor',
  components: {
  },
}
</script>