<!DOCTYPE html>
<html>
  
  <html>
<head>
  
  <title>¡Sorpresa!</title>
  <style>
    /* Establece el tamaño de la ventana de visualización */
    body {
        margin: 0;
        padding: 0;
        overflow: hidden;
        width: 100vw;
        height: 100vh;
    }
    
    /* Crea la animación de fondo */
    @keyframes animatedBackground {
        0% { background-position: 0% 50%; }
        50% { background-position: 100% 50%; }
        100% { background-position: 0% 50%; }
    }
    
    /* Aplica la animación al elemento de fondo */
    .animated-bg {
        position: fixed;
        top: 0;
        left: 0;
        width: 100vw;
        height: 100vh;
        z-index: -1;
        background-image: linear-gradient(to right, #ffafbd, #ffc3a0, #ffafbd);
        background-size: 200% 100%;
        animation: animatedBackground 10s ease-in-out infinite;
    }
</style>

<div class="animated-bg"></div>
<style>
    /* Establece el tamaño de la ventana de visualización */
    body {
        margin: 0;
        padding: 0;
        overflow: hidden;
        width: 100vw;
        height: 100vh;
        font-family: 'Montserrat', sans-serif; /* Cambia 'Montserrat' por el tipo de letra moderna que desees */
    }
    
    /* Crea la animación de fondo */
    @keyframes animatedBackground {
        0% { background-position: 0% 50%; }
        50% { background-position: 100% 50%; }
        100% { background-position: 0% 50%; }
    }
    
    /* Aplica la animación al elemento de fondo */
    .animated-bg {
        position: fixed;
        top: 0;
        left: 0;
        width: 100vw;
        height: 100vh;
        z-index: -1;
        background-image: linear-gradient(to right, #ffafbd, #ffc3a0, #ffafbd);
        background-size: 200% 100%;
        animation: animatedBackground 10s ease-in-out infinite;
    }
</style>

<div class="animated-bg"></div>


  <style>
    body {
      font-family: Arial, Helvetica, sans-serif;
      background-color: #ffffff00;
      margin: 0;
      padding: 20px;
    }
    
    h1 {
      color: #000000;
      text-align: center;
    }
    
    p {
      text-align: center;
      font-size: 48px;
    }
    
    input[type="date"] {
      padding: 10px;
      font-size: 76px;
    }
    
    #cuenta-regresiva {
      font-size: 100px;
      text-align: center;
      margin-top: 20px;
    }
  </style>
  
  <script>
    // Función para actualizar la cuenta regresiva
    function actualizarCuentaRegresiva() {
      // Fecha objetivo: 16 de febrero de 2024
      var fechaObjetivo = new Date("2024-02-16").getTime();
      
      // Obtener la fecha y hora actual
      var fechaActual = new Date().getTime();
      
      // Calcular la diferencia en milisegundos entre las dos fechas
      var diferencia = fechaObjetivo - fechaActual;
      
      // Calcular los días, horas, minutos y segundos restantes
      var dias = Math.floor(diferencia / (1000 * 60 * 60 * 24));
      var horas = Math.floor((diferencia % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
      var minutos = Math.floor((diferencia % (1000 * 60 * 60)) / (1000 * 60));
      var segundos = Math.floor((diferencia % (1000 * 60)) / 1000);
      
      // Mostrar la cuenta regresiva en el elemento con id "cuenta-regresiva"
      document.getElementById("cuenta-regresiva").innerHTML = dias + "d " + horas + "h " + minutos + "m " + segundos + "s ";
      
      // Actualizar la cuenta regresiva cada segundo
      setTimeout(actualizarCuentaRegresiva, 1000);
    }
    
    // Ejecutar la función al cargar la página
    window.onload = function() {
      // Ocultar la página inicialmente
      document.body.style.display = "none";
      
      // Mostrar la página después de 5 segundos (como sorpresa)
      setTimeout(function() {
        document.body.style.display = "block";
        actualizarCuentaRegresiva();
      }, 5000);
    };
  </script>
</head>
<body>
  
  <div id="particles-js"></div>
  <h1>¡Sorpresa Valentina!</h1>
  <div style="visibility: hidden">
    <h1>u</h1>
  </div>
  

  <h1>Fel.. .......!</h1>
 <body>
    <div style="visibility: hidden">
    <h1>u</h1>
    

    
  </div>
  </body>
  <div id="cuenta-regresiva"></div>
</body>

</html>

<head>
  <title>¡Sorpresa!</title>
  
  <style>
    
    body {
      font-family: Helvetica, sans-serif; 
      background-color: #3697bd00;
      margin: 0;
      padding: 20px;
    }
    
    h1 {
      color: #000000;
      text-align: center;
    }
    
    p {
      text-align: center;
      font-size: 78px;
    }
    
    input[type="date"] {
      padding: 10px;
      font-size: 96px;
    }
    .bubbles {
      position: relative;
      display: flex;

     }
     .bubbles span {
      position: relative;
      width: 30px;
      height: 30px;
      background: black;
      margin: 0 4%;
      border-radius: 50%;
      box-shadow: 0 0 0 10px #3697bde5,
      0 0 50px #000000,
      0 0 100px #000000;
      animation: animate 15s linear infinite;

     }
     .bubbles span:nth-child(even) {
      background: #ff2d75;
      box-shadow: 0 0 0 10px #ff2d7544,
      0 0 50px #ff2d75,
      0 0 100px #ff2d75;
     }
    @keyframes animate {
      0% {
        transform: translateY(100vh) scale(0);
      }
      100% {
        transform: translateY(-10vh) scale(1);

      }
    }
    
    #cuenta-regresiva {
      font-size: 124px;
      display: flex;
      height: 80vh;
      margin: 0;
      justify-content: center;
      text-align: center; 
      margin-top: 20px;
    }
    
    #fuegos-artificiales {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      z-index: 9999;
      pointer-events: none;
      background-color: rgba(0, 0, 0, 0.9);
      animation: fireworks 3s linear forwards;
    }
    
    @keyframes fireworks {
      0% {
        opacity: 0;
      }
      50% {
        opacity: 1;
      }
      100% {
        opacity: 0;
      }
    }
    
  </style>
  <script>
    // Función para actualizar la cuenta regresiva
    function actualizarCuentaRegresiva() {
      // Fecha objetivo: 16 de febrero de 2024
      var fechaObjetivo = new Date("2024-02-16").getTime();
      
      // Obtener la fecha y hora actual
      var fechaActual = new Date().getTime();
      
      // Calcular la diferencia en milisegundos entre las dos fechas
      var diferencia = fechaObjetivo - fechaActual;
      
      // Calcular los días, horas, minutos y segundos restantes
      var dias = Math.floor(diferencia / (1000 * 60 * 60 * 24));
      var horas = Math.floor((diferencia % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
      var minutos = Math.floor((diferencia % (1000 * 60 * 60)) / (1000 * 60));
      var segundos = Math.floor((diferencia % (1000 * 60)) / 1000);
      
      // Mostrar la cuenta regresiva en el elemento con id "cuenta-regresiva"
      document.getElementById("cuenta-regresiva").innerHTML = dias + "d " + horas + "h " + minutos + "m " + segundos + "s ";
      
      // Verificar si la cuenta regresiva llegó a cero
      if (diferencia <= 0) {
        // Mostrar los fuegos artificiales
        document.getElementById("fuegos-artificiales").style.display = "block";
      }
      
      // Actualizar la cuenta regresiva cada segundo
      setTimeout(actualizarCuentaRegresiva, 1000);
    }
    
    // Ejecutar la función al cargar la página
    window.onload = function() {
      actualizarCuentaRegresiva();
    };
  </script>
</head>


<body>


