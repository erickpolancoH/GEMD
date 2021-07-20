# GEMD
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Caja de Registro</title>
</head>
<body>
    <style>
        body{
            background-color:black;
            padding: 1%;
            margin: 1%;
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
        }


        h1{
            color: white;
            border: solid rgb(255, 255, 0);
            padding: 1%;
            margin: 1% 0% 3% 0%;
            background-color: transparent;
            position: center;
            font-size: 200%;

         
        }

        h2{
            color: white;
            border: solid rgb(0, 140, 255);
            padding: 1%;
            margin: 1% 0% 1% 0%;
            font-size: 100%;

            
        }

        span {
            color: yellowgreen;
            border:solid white;
            border-radius: 5%;
            padding: 1%;
            margin: 1%;
            
        }
div{
    padding: 1%;
    margin: 1%;
    width: 95%;
    height: 200px;
    background-color: transparent;
    border: solid yellowgreen;
    position: center;

}

p{
    color: rgb(255, 255, 0);
    background-color: transparent;
    border: solid greenyellow;
    padding: 1%;
    margin: 1%;
   font-size: 75%;
   font-weight: 48px;
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;
}

.buttonmsg{
color: white;
background-color: blue;
padding: 1%;
margin: 1%;
font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
}




input#btn-enviar{
    color: white;
    background-color: red;
   overflow: hidden;
   font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
   padding: 1%;
margin: 1%;
}

    </style>

<!--Cuentas de gastos-->

    <h1>
       GEMD Cajas De Registros :)
    </h1>

    <h2>Gastos / Estudio de musica / Pedales de sonido</h2>

 
        <p>Pedal Bass Compressor / pressure point.<span>DOP 1,904</span></p>
        <p>Litle Bear / Guitar Pedal.<span> DOP 2,800</span> </p>
        <p>Stax Booster / Bass Pedal.<span>DOP 1960</span></p>
        <p>Stax flanger / Bass Pedal.<span>DOP 2,000</span></p>
        <button id="Buttonmsg" class="buttonmsg" onclick="showmsg()">Valor Total</button>
       
       
      <!--Archivos subidos-->
       
 

<h2>Documentos subidos</h2>

<form action="procesar.php" method="">

    <input type="file" id="btn-enviar" class="enviar">
</form>




        <script>
            function showmsg (){
                window.alert("El valor total es de [8,694]");
            }
        </script>
</body>
</html>
