# Guión — Lección 6: Errores comunes y próximos pasos


**Duración estimada**: 4 minutos  


---


## Introducción (0:00 – 0:20)


Hola a todos, el día de hoy, vamos a aprender sobre los cinco errores más comunes al aprender HTML y CSS con Plantas versus Zombies

Tu código HTML es tu jardín, las buenas reglas de sintaxis, como las plantas estratégicamente ubicadas, construyen defensas impenetrables que mantienen tu diseño intacto. Los errores de sintaxis, al igual que los zombies, invaden tu documento y rompen la estructura.

---


## Error 1: Olvidar cerrar una etiqueta (0:20 – 0:55)


En el nivel 1, nos enfrentamos a la invasion de las etiquetas sin cerrar. Las etiquetas sin cerrar son como los limites del jardín que debes proteger, por lo que cada etiqueta que abres debe cerrarse con la barra diagonal.


```html
<!-- Incorrecto -->
<h1>Mi título


<!-- Correcto -->
<h1>Mi título</h1>
```


Cuando olvidas cerrar una etiqueta, el navegador puede mostrar el contenido de formas inesperadas: texto que desaparece, secciones que se superponen, o estilos que se aplican a elementos que no debían.


---


## Error 2: Imagen sin atributo alt (0:55 – 1:25)


En el nivel 2 aparece el vacío de las imágenes silenciosas. Esto pasa cuando colocamos una imagen, pero olvidamos el atributo alt, que funciona como una linterna que explica qué hay en la imagen cuando no carga o cuando una persona usa un lector de pantalla. Por eso, una imagen correcta sería al aplicar alt.


```html
<!-- Incorrecto -->
<img src="foto.jpg">


<!-- Correcto -->
<img src="foto.jpg" alt="Descripción de la imagen">
```


---


## Error 3: Olvidar el punto y coma en CSS (1:25 – 2:00)


En el nivel 3 llega la colisión de los estilos en CSS. Aquí el zombie aparece cuando olvidamos el punto y coma. Por ejemplo, no hay punto y coma en medio de red y font-size. Entonces, el navegador puede confundirse porque no sabe dónde termina una regla y dónde empieza la otra. Así que, el punto y coma es como una nuez defensiva que se encarga de separar cada instrucción. 


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


En el nivel 4 tenemos las clases sin placa de identificación, si se quiere plantar un lanza guisantes en el jardín, pero olvidan colocarle su identificación, no se sabe dónde debe colocar la planta y simplemente la ignora. En CSS pasa lo mismo, cuando queremos dar estilo a una clase, debemos poner un punto antes del nombre. Si escribimos tarjeta, el navegador pensará que estamos buscando una etiqueta llamada tarjeta. Pero si escribimos punto tarjeta, entonces sí entiende que es una clase.


```css
/* Incorrecto — el navegador lo ignora */
tarjeta { background-color: white; }


/* Correcto */
.tarjeta { background-color: white; }
```


---


## Error 5: Etiquetas anidadas en orden incorrecto (2:35 – 3:05)


En el nivel 5 aparece el caos de las etiquetas mal anidadas. Esto ocurre cuando abrimos etiquetas en un orden, pero las cerramos en otro. Es como poner plantas en filas desordenadas, la defensa se rompe. La regla es cerrar desde adentro hacia afuera. 



```html
<!-- Incorrecto -->
<h1><p>Texto</h1></p>


<!-- Correcto -->
<h1>Texto</h1>
<p>Texto</p>
```


---


## Cómo validar tu código (3:05 – 3:30)


Finalmente, si no encontramos el error, podemos usar nuestra arma definitiva: el Validador W3C. Es como una cortadora de césped de emergencia que revisa nuestro código y nos dice dónde está la falla.


👉 [https://validator.w3.org](https://validator.w3.org)


Selecciona "Validate by Direct Input", pega tu código y te indicará exactamente dónde están los errores.


---


## Cierre y próximos pasos (3:30 – 4:00)


Hemos llegado al final de esta partida. Las etiquetas están cerradas, las imágenes tienen su descripción, los estilos funcionan correctamente y el jardín sigue en pie.

Puede que en el futuro aparezcan nuevos zombies, pero ahora cuentan con un almanaque de supervivencia para reconocerlos y derrotarlos.

Gracias por acompañarme en esta aventura por el mundo de HTML y CSS.

¡Partida ganada, jardín protegido y código a salvo!



Y no lo olviden, para seguir aprendiendo, tienen estos recursos gratuitos:


- **MDN Web Docs**: [https://developer.mozilla.org/es/](https://developer.mozilla.org/es/)
- **freeCodeCamp en Español**: [https://www.freecodecamp.org/espanol/](https://www.freecodecamp.org/espanol/)


