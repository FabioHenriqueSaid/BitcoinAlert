<template>
  <div id="app">
   <Conversor moeda-a="BTC" moeda-b="BRL"/>
  </div>
</template>

<script>
import Conversor from "./components/Conversor.vue";
export default {
   name:"app",
   components: {
     Conversor
   }
};
</script>


<style> 
 #app{
   font-family: "Avenir";
   -webkit-font-smoothing:antialiased;
   -moz-osx-font-smoothing:grayscale;
   text-align:center;
   columns: #22cc33;
   margin-top:60px;
 }
</style>