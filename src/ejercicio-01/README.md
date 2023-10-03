## Ejercicio 1: Selección de Elementos por ID

Selecciona un elemento por su ID único y cambia su contenido utilizando JavaScript. En este ejercicio, aprenderás a utilizar `getElementById` para acceder a un elemento específico en el DOM y modificar su contenido.

```html
<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Ejercicio 1: Selección de Elementos por ID</title>
  </head>
  <body>
    <div id="miElemento">Texto inicial</div>

    <script>
      const elemento = document.getElementById('miElemento')
      elemento.textContent = 'Nuevo texto'
    </script>

  </body>
</html>
``````