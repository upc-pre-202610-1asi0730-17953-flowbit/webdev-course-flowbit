
# Guión — Lección 3: Elementos HTML: listas, imágenes y enlaces


**Duración estimada**: 6 minutos  


---


## Introducción (0:00 – 0:30)


En la lección anterior aprendiste la estructura básica de HTML y las etiquetas de texto. Ahora agregaremos tres elementos muy comunes en cualquier sitio web: listas, imágenes y enlaces.


---


## Listas (0:30 – 2:00)


HTML tiene dos tipos de listas:


**Lista desordenada** (con puntos):
```html
<ul>
  <li>Escuchar música</li>
  <li>Jugar videojuegos</li>
  <li>Ver series</li>
</ul>
```


**Lista ordenada** (numerada):
```html
<ol>
  <li>Primero esto</li>
  <li>Luego esto</li>
  <li>Finalmente esto</li>
</ol>
```


`<ul>` viene de "unordered list" y `<ol>` de "ordered list". Cada elemento va dentro de una etiqueta `<li>` (list item).


---


## Imágenes (2:00 – 3:30)


Para agregar una imagen se usa la etiqueta `<img>`. Esta etiqueta no tiene cierre, y necesita dos atributos:


```html
<img src="https://url-de-la-imagen.jpg" alt="Descripción de la imagen">
```


- `src` indica la dirección de la imagen (puede ser una URL de internet).
- `alt` es una descripción textual de la imagen. Es importante para personas que usan lectores de pantalla.


Puedes buscar imágenes gratuitas en [Unsplash](https://unsplash.com) y copiar la URL directamente.


---


## Enlaces (3:30 – 5:00)


Los enlaces se crean con la etiqueta `<a>`:


```html
<a href="https://www.wikipedia.org">Visitar Wikipedia</a>
```


- `href` indica la dirección a la que llevará el enlace.
- El texto entre las etiquetas es lo que el usuario verá y podrá hacer clic.


Para que el enlace se abra en una nueva pestaña, agrega `target="_blank"`:


```html
<a href="https://www.wikipedia.org" target="_blank">Visitar Wikipedia</a>
```


---


## Práctica guiada (5:00 – 5:30)


Abre el enlace de JSFiddle en la descripción y completa los 3 pasos indicados en el archivo de inicio.


---


## Cierre (5:30 – 6:00)


Tu página ya tiene estructura y contenido variado. En la siguiente lección aprenderás CSS para darle estilo y que empiece a verse como un sitio web real.


¡Hasta la lección 4!
