<template>
  <div class="container">
    <em>Puedes seleccionar más de un aborno para tu pastel:</em> <br> <br>
    <select class="form-select"  size="12" aria-label="select" multiple id="ornament[]">
      <option value="1">Chantilly</option>
      <option value="2">Caramelo</option>
      <option value="3">Merengue</option>
      <option value="4">Merengue Italiano</option>
      <option value="5">Fondant</option>
      <option value="6">Fruta</option>
    </select>
  </div>
</template>
<script>

export default {
  name: 'DifferentOrnament',
  components: {
  },
}
</script>