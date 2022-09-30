<template>
  <div>
    <h1>Universidad Tecnologica de Tehuacan</h1>
    <h2>APW</h2>
    <h3>Grupo 4B</h3>
    <h1>Directivas en Vue.js</h1>
    <hr/>
    <h2>v-text</h2>
    <span v-text="'Hola desde la directiva v-text'"></span>
    <br>
    <span>Hola desde la directiva v-text</span>
    <br>
    <span v-text="titulo"></span>
    <br>
    Esta es una transmutacion de texto {{titulo}},con una variable props <br>
    <span v-text="titulo"></span>
    <br>
    Hola hola 
    <br>
    
  </div>
</template>

<style scoped>
  div{
    text-align: center;
    margin: 0px 2rem;
  }
</style>
<script>
  export default{
    data:()=>({
      titulo:"Hola desde Vue.js",
    }),
  };
</script>
