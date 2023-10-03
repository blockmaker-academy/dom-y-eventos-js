## Ejercicio 19: Evento de Cambio de Tamaño de Ventana

Utiliza eventos del navegador como `resize` para realizar cambios en la página cuando ocurran estos eventos.

```html
<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Ejercicio 19: Evento de Cambio de Tamaño de Ventana</title>
  </head>
  <body>
    <div id="miDiv">Tamaño de ventana: Desconocido</div>

    <script>
      const div = document.getElementById('miDiv')

      function actualizarTamañoVentana() {
        div.textContent = `Tamaño de ventana: ${window.innerWidth} x ${window.innerHeight}`
      }

      window.addEventListener('resize', actualizarTamañoVentana)
    </script>
  </body>
</html>
```
