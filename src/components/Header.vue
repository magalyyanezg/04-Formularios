<template>
    <div class="container mt-3">
        <div class="row">
          <div class="col-12 col-md-6">
            <h1>Formularios</h1>
          </div>
          <div class="col-12 col-md-6">
            <img :src="url" :alt="alt" width="100">
          </div>
       </div>

       
        <hr />
    </div>
</template>

<script>
  //import Header from "./components/Header.vue"
  import Formulario from "./Formulario.vue"
    export default {
      data:() => ( {
      url:"https://cdn.svgporn.com/logos/vue.svg?response-content-disposition=attachment%3Bfilename%3Dvue.svg",
      alt: "Vue.js",
      nombre:"",
      edad:0,
      correo:"",  
      Formulario,
    }),
  
    };
    
  </script>