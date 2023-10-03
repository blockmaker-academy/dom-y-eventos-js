## Ejercicio 4: Selección de Elementos con `querySelectorAll`

Utiliza `querySelectorAll` para seleccionar todos los elementos de un tipo específico y ocultarlos. Aprenderás cómo seleccionar varios elementos y aplicar una acción a todos ellos.

```html
<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Ejercicio 4: Selección de Elementos con `querySelectorAll`</title>
  </head>
  <body>
    <p>Primer párrafo</p>
    <p>Segundo párrafo</p>
    <p>Tercer párrafo</p>

    <script>
      const elementos = document.querySelectorAll('p')
      elementos.forEach((elemento) => {
        elemento.style.display = 'none'
      })
    </script>
  </body>
</html>
```
