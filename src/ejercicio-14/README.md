## Ejercicio 14: Detener la Propagación de Evento

Utiliza `stopPropagation` para evitar que un evento se propague a elementos padre. Aprenderás cómo evitar que los eventos se propaguen en el árbol DOM.

```html
<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Ejercicio 14: Detener la Propagación de Evento</title>
  </head>
  <body>
    <div id="elementoPadre">
      <div id="elementoHijo">Haz clic aquí</div>
    </div>

    <script>
      const elementoHijo = document.getElementById('elementoHijo')
      elementoHijo.addEventListener('click', (evento) => {
        evento.stopPropagation()
        alert('Evento hijo')
      })

      const elementoPadre = document.getElementById('elementoPadre')
      elementoPadre.addEventListener('click', () => {
        alert('Evento padre')
      })
    </script>
  </body>
</html>
```
