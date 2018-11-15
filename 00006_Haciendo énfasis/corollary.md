¿Notaste eso? :eyes: 

Tanto el contenido de un `h1` como un de `p` se separa del siguiente elemento con un "enter" :leftwards_arrow_with_hook:. Por eso a éstos se los conoce como _agrupadores de bloque_. Si nos imaginamos a cada etiqueta como un bloque de color rosa, sería algo así:

<div style="width: 70%; margin: auto;">
  <table class="table">
  <tr>
  <div style="
   padding: 1%;
   margin: 1%;
   border-color: #FF5B81;
   border-style: solid;
   text-align: center;
   border-radius: 5px;
  ">
  <h3>¡Soy un encabezado!</h3>
  </div>
  </tr>
  
  <tr>
  <div style="
   padding: 1%;
   margin: 1%;
   border-style: solid;
   border-color: #FF5B81;
   text-align: center;
   border-radius: 5px;
  ">
  <p>Y yo... ¡un párrafo! Y estamos separados por un espacio.</p>
</div>
  <tr> 
</table>
</div>

En cambio, `strong` o `em` permiten realizar _agrupaciones en línea_. Es decir, le dan una apariencia distinta a cierta parte del texto sin interrumpir el mismo. Y si seguimos utilizando nuestra imaginación :rainbow: y cada etiqueta fuese un bloque de color azul, sería algo así: 

<html>
<head>
     <meta charset="UTF-8">
 </head>
<div style="
   padding: 1%;
   margin: 1%;
   border-color: #FF5B81;
   border-style: solid;
   border-radius: 5px;
   width: 70%;
   margin: auto;
   text-align:center;
">
<span>
  Acá vemos como las palabras
</span>
<span style="
   padding: 1%;
   margin: 1%;
   border-color: #0B465D;
   border-style: solid;
   border-radius: 5px;
   text-align:center;
"> <strong>negritas</strong>
</span>
<span>
  y
</span>
<span style="
   padding: 1%;
   margin: 1%;
   border-color: #0B465D;
   border-style: solid;
   border-radius: 5px;
   text-align:center;
"> <em>enfatizadas</em>
</span>
<span>
  quedan en una misma línea. 😯 
</span>
   </div>
   </html>