## Ejercicio 18: Evento Personalizado y Disparo

Crea un evento personalizado y asígneselo a un elemento, luego escucha ese evento y realiza una acción cuando se dispara.

```html
<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Ejercicio 18: Evento Personalizado y Disparo</title>
  </head>
  <body>
    <button id="miBoton">Disparar Evento Personalizado</button>

    <script>
      const boton = document.getElementById('miBoton')

      function crearEventoPersonalizado() {
        const eventoPersonalizado = new Event('eventoPersonalizado')
        boton.dispatchEvent(eventoPersonalizado)
      }

      boton.addEventListener('eventoPersonalizado', () => {
        alert('¡Evento personalizado disparado!')
      })

      boton.addEventListener('click', () => {
        crearEventoPersonalizado()
      })
    </script>
  </body>
</html>
```
