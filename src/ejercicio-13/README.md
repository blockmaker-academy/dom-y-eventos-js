## Ejercicio 13: Prevenir la Acción por Defecto de un Enlace

Utiliza `preventDefault` para evitar que un enlace navegue a otra página cuando se hace clic. Este ejercicio te mostrará cómo controlar el comportamiento predeterminado de un evento.

```html
<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Ejercicio 13: Prevenir la Acción por Defecto de un Enlace</title>
  </head>
  <body>
    <a id="miEnlace" href="https://www.ejemplo.com">Enlace</a>

    <script>
      const enlace = document.getElementById('miEnlace')
      enlace.addEventListener('click', (evento) => {
        evento.preventDefault()
        alert('Enlace bloqueado')
      })
    </script>
  </body>
</html>
```
