## Ejercicio 7: Cambio de Atributos con `setAttribute`

Utiliza `setAttribute` para establecer o modificar el valor de un atributo en un elemento HTML. En este ejercicio, aprenderás a cambiar los atributos de un elemento.

```html
<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Ejercicio 7: Cambio de Atributos con `setAttribute`</title>
  </head>
  <body>
    <div id="miElemento">Elemento con atributo</div>

    <script>
      const elemento = document.getElementById('miElemento')
      elemento.setAttribute('data-nuevo', 'valor')
    </script>
  </body>
</html>
```
