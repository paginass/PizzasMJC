# PizzasMJC
Pagina de pizzas - Monserrat Cerrito Jimenez
<!DOCTYPE html>
<html>

<head>
   <meta charset="UTF-8">
   <meta name='viewport' content='width-divace-width, initial-scale=1, shrink-to-fit=no'>
   <link href='https://cdn.jsdelivr.net/npm/boxicons@2.0.5/css/boxicons.min.css' rel='stylesheet'>
   <link rel="shortcut icon" href="imagenes/logooo - copia.png">
   <link rel="stylesheet" href="CSS Pizzas.css">
   <title>Pancho's Pizza</title>
</head>


<body>
   <div class="barr">
      <div class="agust">
         <div class="titulo">
            <a href="EjemploFormularioHTML.html"> <img src="imagenes/logooo - copia.png"></a>
           
            <h3> <b> Pedidos de Pancho's Pizza</b></h3>
         </div>
         <ul>
            <li><a href="#">Promociones</a></li>
            <li><a href="#">Carrito</a></li>
            <li><a href="#">Login</a></li>
         </ul>
      </div>
   </div>
   <div class="baner">
      <br><br><br>

      <form class="menu">
         <fieldset class="selector">
            <legend>La Pizzone</legend>
            <div class="ord">

               <div>
                  <img src="imagenes/various-pizzas-set.png">
               </div>
               <div>
                  <p>INGREDIENTES</p>
                  <input type="checkbox" name="queso" /> <label>Queso</label><br>
                  <input type="checkbox" name="pimiento" /> <label>Pimiento</label><br>
                  <input type="checkbox" name="cebolla" /><label> Cebolla</label>
               </div>
               <div>
                  <p>TAMAÑO</p>
                  <input type="radio" name="tamano" required /><label> Pequeña</label><br>
                  <input type="radio" name="tamano" required /><label> Mediana </label><br>
                  <input type="radio" name="tamano" required /> <label>Grande</label>
               </div>
            </div>
         </fieldset>
         <br>
         <fieldset class="selector">
            <legend>Datos De Entrega</legend>
            <div class="ali">
               <div class="mamalon">
                  <div>
                     <label>Nombre</label> <br>
                     <label>Dirección </label> <br>
                     <label>Teléfono </label> <br>
                  </div>
                  <div class="chido">
                     <input type="text" name="NOMBRE" required><br>
                     <input type="text" name="DIRECCIÓN" required><br>
                     <input type="tel" name="TELEFONO" required><br>
                  </div>
               </div>
               <div class="cuadro">
                  <label>Instrucciones Especiales</label><br /><textarea cols="40" rows="7"></textarea>
               </div>
            </div>
         </fieldset>
         <br>
         <fieldset class="pago">
            <legend>Método Del Pago</legend>
            <select class=met required>
               <option>Efectivo</option>
               <option>VISA</option>
               <option>Otso</option>
            </select>
         </fieldset>
         <br>
         <div class="bot">
            <input type="submit" id="ok" value="Enviar pedido">
         </div>
      </form>
   </div>
   <br>
</body>
<footer>
   <div class="pieOrd">
      <p> &copy; Derechos Reservados - Pancho's Pizza 2022 </p>
<p>BY: Monserrat Cerrito Jiménez</p>
      <div>
         <p>Siguenos en nuestras redes sociales</p>
         <br>
         <div class="just">
            <i class='bx bxl-twitter'></i>
            <i class='bx bxl-facebook-circle'></i>
            <i class='bx bxl-instagram'></i>
            <i class='bx bxl-youtube'></i>
         </div>
      </div>
   </div>
</footer>

</html>
