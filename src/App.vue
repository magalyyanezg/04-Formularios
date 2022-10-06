<template>
  <div class="container mt-3">
    <Header />
   
    <form>
      <div class="mb-3">
        <label for="exampleInputEmail1" class="form-label">Proyecto</label>
        <input type="text" class="form-control" id="exampleInputProject" aria-describedby="projectHelp">
      </div>
      <div class="mb-3">
        <label for="exampleInputPassword1" class="form-label">Actividad</label>
        <input type="text" class="form-control" id="exampleInputPassword1">
      </div>
      <div class="mb-3 form-check">
        <input type="checkbox" class="form-check-input" id="exampleCheck1">
        <label class="form-check-label" for="exampleCheck1">Urgente</label>
      </div>
      <button type="submit" class="btn btn-primary">Guardar</button>
    </form>

  </div>
</template>

<script>
  
  //import Header from "./components/Header.vue"
  import Formulario from "./components/Formulario.vue"
  export default {
    components: {
      Formulario,
    }
  }
</script>

<style scoped>
  body {
    margin: 0px 2rem;
  }
</style>