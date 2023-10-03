## Ejercicio 12: Asociar Evento de Clic

Asocia un evento de clic a un botón y muestra un mensaje cuando se hace

clic en el botón. Aprenderás cómo responder a eventos de usuario.

```html
<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Ejercicio 12: Asociar Evento de Clic</title>
  </head>
  <body>
    <button id="miBoton">Haz clic</button>

    <script>
      const boton = document.getElementById('miBoton')
      boton.addEventListener('click', () => {
        alert('¡Hiciste clic en el botón!')
      })
    </script>
  </body>
</html>
```
