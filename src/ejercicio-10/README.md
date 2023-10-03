## Ejercicio 10: Agregar Elemento con `appendChild`

Utiliza `appendChild` para agregar un nuevo elemento como hijo de otro elemento existente en el DOM. Aprenderás a crear y agregar elementos dinámicamente.

```html
<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Ejercicio 10: Agregar Elemento con `appendChild`</title>
  </head>
  <body>
    <div id="contenedor">Contenido existente</div>
    <button id="miBoton">Agregar Elemento</button>

    <script>
      const nuevoElemento = document.createElement('div')
      nuevoElemento.textContent = 'Nuevo elemento'
      const contenedor = document.getElementById('contenedor')
      contenedor.appendChild(nuevoElemento)
    </script>
  </body>
</html>
```
