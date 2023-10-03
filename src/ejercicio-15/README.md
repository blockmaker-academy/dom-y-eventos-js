## Ejercicio 15: Delegación de Eventos

Utiliza la delegación de eventos para manejar clics en varios elementos de una lista a través de un elemento padre común. Este ejercicio te muestra cómo simplificar el manejo de eventos en elementos múltiples.

```html
<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Ejercicio 15: Delegación de Eventos</title>
  </head>
  <body>
    <ul id="miLista">
      <li>Elemento 1</li>
      <li>Elemento 2</li>
      <li>Elemento 3</li>
    </ul>

    <script>
      const lista = document.getElementById('miLista')
      lista.addEventListener('click', (evento) => {
        if (evento.target.tagName === 'LI') {
          alert('Clic en un elemento de la lista')
        }
      })
    </script>
  </body>
</html>
```
