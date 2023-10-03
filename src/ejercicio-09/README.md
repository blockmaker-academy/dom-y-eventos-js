## Ejercicio 9: Manipulación de Clases con `classList`

Agrega una clase a un elemento utilizando `classList` en JavaScript. Este ejercicio te mostrará cómo manipular las clases de un elemento.

```html
<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Ejercicio 9: Manipulación de Clases con `classList`</title>
  </head>
  <body>
    <div id="miElemento">Elemento con clase</div>

    <script>
      const elemento = document.getElementById('miElemento')
      elemento.classList.add('nuevaClase')
    </script>
  </body>
</html>
```
