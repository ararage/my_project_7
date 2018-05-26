<template>
  <div class="container">
    <div class="jumbotron">
      <mostrarFormulario>
        <div slot="titulo">
          <h3>Cambiar Clave</h3>
        </div>
        <div slot="elementos">
          <div class="form-group">
              <label for="correo">Correo Electrónico</label>
              <input type="email" class="form-control" id="correo" placeholder="Escribe tu correo electrónico">
          </div>
          <div class="form-group">
              <label for="clave">Contraseña</label>
              <input type="password" class="form-control" id="clave" placeholder="Escribe tu contraseña">
          </div>
        </div>
        <div slot="boton">
          <button class="btn btn-primary">Cambiar Clave</button>
        </div>
      </mostrarFormulario>
    </div>
  </div>
</template>

<script>
import MostrarFormulario from './components/MostrarFormulario.vue'
export default {
  components: {
      mostrarFormulario: MostrarFormulario,
      cambiarClave: CambiarClave
  },
  data () { 
  }
}
</script>

<style scoped>
  h3{
    color: red;
  }
</style>
