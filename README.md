<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!--Link de Css-->
    <link rel="stylesheet" href="estilos/style.css">
    <!--bt-->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <title>Lupita Love</title>
</head>
<body>
<header class="header"> <!--Logo, Menu-->
    <img class="logo" src="images/Photoroom_20240727_003609.png" alt="Imagen de logo">
    <nav>
        <ul class="menu-inicio">
            <li class="menu"><a class="item">Inicio</a></li>
            <li class="menu"><a  class="nav-link dropdown-toggle" data-bs-toggle="dropdown" href="enlace.html" role="button" aria-expanded="truse">Productos</a></li>
            <li class="menu"><a class="item" href="enlace.html">Contactos</a></li>
        </ul>
</nav>
</header>
<!--Imagen, descripcion -->
<main class="main-container"> 
    <div class="container">
        <h2>Cartera Minibag Negra</h2>
        <img class="img-uno" src="images/WhatsApp Image 2024-06-29 at 20.06.55 (1).jpeg" alt="Cartera">
        <p class="Mini-bag">Minibag lupita </p>
        <a class="enlace" href="minibag.html">Ver mas</a>
    </div>
    <div class="container">
        <h2>Mochila Joup Marron</h2>
        <img class="img-dos" src="images/WhatsApp Image 2024-06-29 at 20.06.56 (1).jpeg" alt="Mochila">
        <p id="mochila-brown">Mochila Brown</p><a class="Boton" href="joup.html">Ver más</a>
    </div>
</main>
<!--Redes, derechos-->
<footer class="footer">
    <div class="redes">
        <a class="instagram" href="https://www.instagram.com/luupitalovee/?hl=es-la">logo de instagram</a>
    <img class="instagram-2" src="symbol-instagram.png" alt="Logo de instagram">
    </div>
    <div>
        <p class="texto">Todos los derechos reservados - 2024 </p>
    </div>
</footer>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
</body>
</html>
/*reset*/
* {
    margin: 0%;
    padding: 0%;
    box-sizing: border-box;
  }
  /*header*/
  .header {
    display: flex;
    height: 100px;
    padding: 8px, 10%;
    align-items: center;
    justify-content: space-between;
    background-color: #a0f0f0;
  }
  
  header img {
    margin: 0%;
    padding: 0%;
    height: 100px;
    cursor: pointer;
    transition: all 0, 3s;
  }
  
  header ul {
    list-style: none;
    text-decoration: none;
    display: flex;
    margin-right: 20px;
    justify-content: center;
    gap: 20px;
  }
  
  header .item {
    text-decoration: none;
    color: black;
    justify-content: space-between;
  }
  /*Estilo de main*/
  @import url('https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap');
  main div img {
    width: 200px;
    height: 250px;
    padding: 5%;
    margin: left;
    top: 100%;
  }
  main {
    width: 300px;
    height: 200px;
    display: flex;
    flex-grow: initial;
    grid-template-columns: repeat(2,1fr);
    grid-template-rows: max-content;
  }
  
  .main .h2 {
    font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    text-align: start;
    font-size: large;
    color: black;
    text-decoration: solid;
  }
  
main div .img-uno{
    height: 300px;
    width: 200px;
    justify-content: space-between;
  }
main div .img-dos{
    height: 300px;
    width: 150px;
    flex-direction: column-reverse;
}
  @media only screen and (max-width: 360px){
  body{display: flex;}  
  
}
  /*txt*/
  h2 {
    font-size: 25px;
    color: black;
    text-align: start;
  }
  
  h3 {
    font-size: 25px;
    color: black;
    text-align: center;
  }
  
  p {
    font-size: medium;
    text-align: start;
    text-decoration: dotted;
  }
  
  .p {
    font-size: medium;
    text-align: start;
  }
  
  /*footer-redes*/
  footer div a{
    margin-right: auto;
    width:100%;
    height:200px;
    background-color:red;
  }
  /*botones*/
  .boton {
    color: blue;
    font-size: medium;
    font-weight: bold;
  }
  
