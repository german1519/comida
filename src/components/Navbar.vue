<template>
<body>

<h1>FASTFOOD</h1>
<h2>German Martinez Correo 10 A</h2>

<div class="navbar">
  <a class="active" href="#"><i class="fa fa-fw fa-home"></i>Inicio</a> 
  <a href="#"><i class="fa fa-fw fa-search"></i>Galeria</a> 
  <a href="#"><i class="fa fa-fw fa-envelope"></i> Contacto</a> 
  <a href="#"><i class="fa fa-fw fa-user"></i>Ubicacion</a>
</div>
</body>

</template>


<style>
body {font-family: Arial, Helvetica, sans-serif;}
h1{
  background-color: #F27649;
  color: #fff;
}

.navbar {
  width: 100%;
  background-color: #F27649;
  overflow: auto;
}

.navbar a {
  float: left;
  padding: 12px;
  color: white;
  text-decoration: none;
  font-size: 17px;
}

.navbar a:hover {
  background-color: #854129 ;
}

.active {
  background-color: #854129;
}

@media screen and (max-width: 500px) {
  .navbar a {
    float: none;
    display: block;
  }
}
</style>

<script>    
</script>