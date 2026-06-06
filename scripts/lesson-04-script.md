# Guión — Lección 4: CSS: estilos, colores y diseño


**Duración estimada**: 12 minutos  


---


## Introducción (0:00 – 0:40)


Hasta ahora nuestra página tiene contenido pero se ve bastante simple. En esta lección aprenderemos CSS, el lenguaje que usamos para darle estilo visual a todo lo que ya escribimos en HTML.


---


## ¿Qué es CSS y cómo se vincula con HTML? (0:40 – 2:00)


CSS se escribe dentro de una etiqueta `<style>` que va en el `<head>` del documento:


```html
<head>
  <title>Mi página</title>
  <style>
    /* Aquí van los estilos */
  </style>
</head>
```


---


## Selectores y propiedades (2:00 – 4:00)


CSS funciona con esta estructura:


```css
selector {
  propiedad: valor;
}
```


Por ejemplo, para cambiar el color de todos los títulos `<h1>`:


```css
h1 {
  color: blue;
}
```


Los selectores más comunes son:
- Por etiqueta: `h1`, `p`, `body`
- Por clase: `.mi-clase` (se agrega con el atributo `class="mi-clase"` en HTML)
- Por id: `#mi-id` (se agrega con el atributo `id="mi-id"` en HTML)


---


## Colores y fuentes (4:00 – 6:30)


Propiedades para texto y colores:


```css
body {
  background-color: #f0f0f0;
  font-family: Arial, sans-serif;
}


h1 {
  color: #2c7bb6;
  font-size: 40px;
  text-align: center;
}
```


Los colores se pueden escribir como:
- Nombre en inglés: `red`, `blue`, `lightblue`
- Código hexadecimal: `#ff0000` (rojo), `#2c7bb6` (azul)


---


## Márgenes, relleno y bordes (6:30 – 9:00)


Estas tres propiedades controlan el espacio alrededor de los elementos:


```css
p {
  margin: 20px;    /* espacio exterior al elemento */
  padding: 16px;   /* espacio interior al elemento */
  border: 2px solid #333;  /* borde del elemento */
}
```


Una forma fácil de recordarlo:
- `margin` es la distancia entre el elemento y lo que lo rodea por fuera.
- `padding` es la distancia entre el borde y el contenido interior.


---


## Clases en CSS (9:00 – 10:30)


Cuando queremos aplicar un estilo solo a algunos elementos y no a todos, usamos clases.


En HTML:
```html
<p class="destacado">Este párrafo tendrá estilo especial.</p>
<p>Este párrafo no.</p>
```


En CSS:
```css
.destacado {
  background-color: #fffbcc;
  border-left: 4px solid #f0c040;
  padding: 12px;
}
```


---


## Práctica guiada (10:30 – 11:30)


Abre el enlace de JSFiddle en la descripción. El archivo de inicio tiene dos partes: `index.html` con el contenido listo, y `styles.css` con los 5 pasos que debes completar.


---


## Cierre (11:30 – 12:00)


Tu página ya tiene estilo. En la siguiente lección combinarás todo lo aprendido para construir tu página de perfil personal completa.


¡Hasta la lección 5!
