<template>

<Navbar/>

  <card url="https://cdn.pixabay.com/photo/2017/03/23/19/57/asparagus-2169305__340.jpg" nombre="Corte cherrie" precio= "$ 120" descripcion="Esparragos filete de carne"/>
  <card url="https://cdn.pixabay.com/photo/2015/04/08/13/13/food-712665_960_720.jpg" nombre="Salmon" precio= "$ 250" descripcion="Comida Salmon Teriyaki"/>
  <card url="https://cdn.pixabay.com/photo/2014/04/22/02/56/pizza-329523_960_720.jpg" nombre="Pizza" precio= "$ 80" descripcion="Pizza rodajas cocina italiana"/>
  <card url="https://cdn.pixabay.com/photo/2014/11/05/15/57/salmon-518032_960_720.jpg" nombre="Pescado" precio= "$ 180" descripcion="Salmon pez fruto de mar"/>
  <card url="https://cdn.pixabay.com/photo/2017/01/30/13/49/pancakes-2020863_960_720.jpg" nombre="Pan" precio= "$ 90" descripcion="Panqueques crepe tortilla"/>
  <card url="https://cdn.pixabay.com/photo/2016/11/22/23/45/pancakes-1851249_960_720.jpg" nombre="Postre" precio= "$ 50" descripcion="Crema batida"/>
<br>

<br>
<br>
  <Footer/>

</template>


<style>

</style>

<script>


  import Card from "./components/Card.vue";
  import Navbar from "./components/Navbar.vue";
  import Footer from "./components/Footer.vue"


  export default{
    components: { Card, Navbar, Footer}
  }
</script>

