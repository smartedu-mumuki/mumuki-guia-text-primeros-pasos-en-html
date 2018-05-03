¿Es posible que una lista se muestre horizontal?
Te diste cuenta que el elemento `li` agrupa como bloque, entonces siempre cada elemento quedo uno debajo del otro. Pero esto, como ya vimos, podemos arreglarlo usando `display`. 
¿Y en qué caso quisiera una lista horizontal? Bueno, son muy utilizadas en las barras de navegación.

> Escribí los siguiente en el cuadro de la derecha:
>
> ```
> <!DOCTYPE html>
> <html>
> <head>
> <style>
> ul {
>     list-style-type: none;
> }
> 
> li {
    display: inline;
    text-align: center;
    padding: 16px;
}
</style>
</head>
<body>
<nav>
<ul>
  <li>Portada</li>
  <li>Noticias</li>
  <li>Contacto</li>
  <li>Sobre mi</li>
</ul>
</nav>
</body>
</html>
> ```
