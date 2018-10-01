¿Y si queremos una lista ordenada?

¡Muy fácil! En lugar de usar `ul` vamos a usar `ol`. Pero tranqui, los items se siguen llamando `li`.

La diferencia es que tiene un atributo llamado `type` que permite modificar el formato del índice utilizado:

- 1: índice numérico (por defecto)
- A: índice alfabético
- I: índice romano

Por ejemplo este código...

``` html
<ol type="A"> Canciones del album "Invisible":
  <li>Jugo de lúcuma</li>
  <li>El diluvio y la pasajera</li>
  <li>Suspensión</li>
  <li>Tema de Elmo Molesto</li>
  <li>Azafata del tren fantasma</li>
  <li>Irregular</li>
</ol>
```

... se vería así:

<ol type="A"> Canciones del album "Invisible":
  <li>Jugo de lúcuma</li>
  <li>El diluvio y la pasajera</li>
  <li>Suspensión</li>
  <li>Tema de Elmo Molesto</li>
  <li>Azafata del tren fantasma</li>
  <li>Irregular</li>
</ol>

> ¡Ahora te toca a vos! Lista 3 elementos usando el índice numérico (es decir, no hace falta escribir el `type`).
