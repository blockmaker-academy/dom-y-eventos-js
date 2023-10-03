## Ejercicio 17: Manejo de Evento de Carga de Imagen

Maneja el evento de carga de una imagen y muestra un mensaje cuando la imagen se carga.

```html
<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Ejercicio 17: Manejo de Evento de Carga de Imagen</title>
  </head>
  <body>
    <img id="miImagen" src="imagen.jpg" alt="Imagen" />

    <script>
      const imagen = document.getElementById('miImagen')

      imagen.addEventListener('load', () => {
        alert('La imagen se ha cargado correctamente')
      })
    </script>
  </body>
</html>
```
