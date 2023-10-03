## Ejercicio 3: Selección de Elementos con `querySelector`

Utiliza `querySelector` para seleccionar un elemento de un formulario y cambia su valor utilizando JavaScript. Aprenderás cómo seleccionar un elemento específico de un formulario y modificar su contenido.

```html
<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Ejercicio 3: Selección de Elementos con `querySelector`</title>
  </head>
  <body>
    <input type="text" id="miInput" value="Valor inicial" />

    <script>
      const inputElement = document.querySelector('input[type="text"]')
      inputElement.value = 'Nuevo valor'
    </script>
  </body>
</html>
```
