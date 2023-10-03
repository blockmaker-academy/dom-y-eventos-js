## Ejercicio 6: Cambio de Contenido con `innerHTML`

Modifica el contenido HTML de un elemento utilizando `innerHTML` en JavaScript. Aprenderás cómo agregar contenido HTML adicional a un elemento existente.

```html
<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Ejercicio 6: Cambio de Contenido con `innerHTML`</title>
  </head>
  <body>
    <div id="miElemento">Texto inicial</div>

    <script>
      const elemento = document.getElementById('miElemento')
      elemento.innerHTML = '<strong>Nuevo contenido HTML</strong>'
    </script>
  </body>
</html>
```
