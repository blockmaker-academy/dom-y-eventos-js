## Ejercicio 5: Cambio de Contenido con `textContent`

Cambia el texto contenido dentro de un elemento utilizando `textContent` en JavaScript. Este ejercicio te mostrará cómo modificar el texto visible en un elemento HTML.

```html
<html lang="es">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Ejercicio 5: Cambio de Contenido con `textContent`</title>
  </head>
  <body>
    <div id="miElemento">Texto inicial</div>

    <script>
      const elemento = document.getElementById('miElemento')
      elemento.textContent = 'Nuevo texto'
    </script>
  </body>
</html>
```
