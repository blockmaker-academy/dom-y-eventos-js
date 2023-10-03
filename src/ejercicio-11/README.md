## Ejercicio 11: Eliminar Elemento con `removeChild`

Utiliza `removeChild` para eliminar un elemento hijo de su elemento padre en el DOM. Aprenderás a quitar elementos del árbol DOM.

```html
<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Ejercicio 11: Eliminar Elemento con `removeChild`</title>
  </head>
  <body>
    <div id="contenedor">
      <div id="elementoAEliminar">Elemento a eliminar</div>
    </div>

    <script>
      const elementoAEliminar = document.getElementById('elementoAEliminar')
      const padre = elementoAEliminar.parentElement
      padre.removeChild(elementoAEliminar)
    </script>
  </body>
</html>
```
