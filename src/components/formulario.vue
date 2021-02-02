<template>
  <div id="formulario">
    <div class="container-form">
      <h3>Contactanos</h3>
        <div class="form-row">
          <div class="form-group col-md-6">
            <label for="inputName">Nombre</label>
            <input type="name" class="form-control" id="inputName" placeholder="Nombre">
          </div>
          <div class="form-group col-md-6">
            <label for="inputUsername">Apellido</label>
            <input type="Username" class="form-control" id="inputUsername" placeholder="Apellido">
          </div>
          <div class="form-group col-md-6">
            <label for="inputEmail4">Email</label>
            <input type="email" class="form-control" id="inputEmail4" placeholder="Email">
          </div>
          <div class="form-group col-md-6">
            <label for="inputTelefono">Teléfono</label>
            <input type="telefono" class="form-control" id="inputTelefono" placeholder="Telefono">
          </div>
      </div>
      <div class="form-group">
        <label for="inputAddress">Dirección</label>
        <input type="text" class="form-control" id="inputAddress" placeholder="av.palau 123">
      </div>
      <div class="form-row">
        <div class="form-group col-md-4">
          <label for="inputCity">Ciudad</label>
          <select id="inputCity" class="form-control">
            <option value="1">Madrid</option>
            <option value="2">Barcelona</option>
            <option value="3">Valencia</option>
          </select>
        </div>
        <div class="form-group col-md-2">
          <label for="inputZip">CP</label>
          <input type="text" class="form-control" id="inputZip">
        </div>
      </div>
      <div class="form-group">
        <div class="form-check">
          <input class="form-check-input" type="checkbox" id="gridCheck">
          <label class="form-check-label" for="gridCheck">
            Acepto las condiciones
          </label>
        </div>
      </div>
      <button type="submit" class="btn btn-primary">ENVIAR</button>
    </div>
  </div>
</template>

<script>
export default {
  name: "formulario",

}
</script>
<style scoped>
h3{
  padding: 18px;
}
#formulario{
  background: pink;
  height: 600px;
  width: 100%;
}
.container{
  background: white;
  height: 500px;
  width: 500px;

}

</style>