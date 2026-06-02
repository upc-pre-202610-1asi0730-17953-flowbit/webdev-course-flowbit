# Guión — Lección 6: Errores comunes y próximos pasos


**Duración estimada**: 4 minutos  


---


## Introducción (0:00 – 0:20)


En esta última lección vamos a ver los cinco errores más frecuentes al escribir HTML y CSS. Los veremos directamente en código para que los reconozcas fácilmente cuando te ocurran.


---


## Error 1: Olvidar cerrar una etiqueta (0:20 – 0:55)


Este es el error más común. Cada etiqueta que abres debe cerrarse con la barra diagonal.


```html
<!-- Incorrecto -->
<h1>Mi título


<!-- Correcto -->
<h1>Mi título</h1>
```


Cuando olvidas cerrar una etiqueta, el navegador puede mostrar el contenido de formas inesperadas: texto que desaparece, secciones que se superponen, o estilos que se aplican a elementos que no debían.


---


## Error 2: Imagen sin atributo alt (0:55 – 1:25)


El atributo `alt` no es opcional. Describe la imagen para personas que usan lectores de pantalla o cuando la imagen no carga.


```html
<!-- Incorrecto -->
<img src="foto.jpg">


<!-- Correcto -->
<img src="foto.jpg" alt="Descripción de la imagen">
```


---


## Error 3: Olvidar el punto y coma en CSS (1:25 – 2:00)


En CSS, cada línea de estilo termina con punto y coma. Si lo omites, el navegador puede ignorar esa propiedad o las que siguen.


```css
/* Incorrecto */
h1 {
  color: red
  font-size: 32px
}


/* Correcto */
h1 {
  color: red;
  font-size: 32px;
}
```


---


## Error 4: Clase CSS sin el punto (2:00 – 2:35)


Cuando defines una clase en CSS, el nombre siempre lleva un punto al inicio. Sin ese punto, el navegador no sabe que es una clase y el estilo no se aplica.


```css
/* Incorrecto — el navegador lo ignora */
tarjeta { background-color: white; }


/* Correcto */
.tarjeta { background-color: white; }
```


---
