# Bienvenidos alumnos!
Este repositorio compila todo el contenido dado sobre HTML, CSS y Bootstrap de los primeros dos días del Bootcamp. Todo el contenido dado está en las carpetas correspondientes, corregidos y actualizados.

# Estructura

Los contenidos están en las carpetas. Cuando repasen, recomiendo respetar el mismo orden en el que dimos en la clase, primero HTML, después CSS y por último Bootstrap.

## HTML

Acá coloco algunos *tips* importantes referentes a HTML.
- HTML **no** es un lenguaje de programación;
- La versión actual es la 5.2 (HTML 5.2);
- Siempre declaren el DOCTYPE `<!DOCTYPE html>`;
- Declaren la codificación `<meta charset="UTF-8">`.

### Links de referencia
- https://www.w3c.es/ \- Sitio web del consorcio regulador de la WWW;
- https://www.w3.org/TR/2017/REC-html52-20171214/ Estándar HTML 5.2, la ultima versión lanzada de HTML (inglés);
- https://www.w3schools.com/html/default.asp \- Sitio Web didáctico sobre HTML y tecnologías Web, recomendado para aprender más etiquetas HTML (inglés);
    
-   https://developer.mozilla.org/es/ \- Mozilla Developer Network, sitio Web con mucha documentación sobre tecnologías Web.
    
-   https://developer.mozilla.org/es/docs/Web/HTML/Elemento - Documentación de elementos HTML
    
-   https://code.visualstudio.com/ \- Sitio Web del editor de texto Visual Studio Code.
## CSS

CSS es bastante amplio, pero las cosas más importantes son siempre respetar el **box model**, los tipos de **display**.

Recuerden que los bloques de estilo se aplican a etiquetas, selectores id `#id {}` y a selectores de clase o *class* `.clase {}`.

Cuando estén realizando algún desarrollo en CSS, asegúrense de probar en varios navegadores, por lo menos con la última versión estable de los mismos. No está demás tampoco usar herramientas como [Normalize.CSS](https://necolas.github.io/normalize.css/) (gracias Mr. [@rorogarcete](https://github.com/rorogarcete)).

**P.D.:** En la carpeta también tenemos el video compartido por el compañero de cómo aprovechar el [Grid Layout](https://developer.mozilla.org/es/docs/Web/CSS/CSS_Grid_Layout) para montar una plataforma similar a Pinterest sin ninguna libreria externa.

### Algunos links de referencia
-   https://www.w3schools.com/css/css_boxmodel.asp \- Explicación del modelo de caja;
    
-   https://developer.mozilla.org/es/docs/Web/CSS \- Sección de CSS en el MDN;
    
-   https://www.w3schools.com/css/default.asp \- Descripción y uso de cada propiedad;
    
-   https://www.materialui.co/htmlcolors \- Sitio Web con varios colores HTML para copiar y usar;
    
-   https://www.w3schools.com/colors/colors_names.asp \- Más colores HTML.

## Bootstrap

Finalmente, pero para nada menos importante, tenemos la sección de Bootstrap. Recuerden que bootstrap es un framework muy poderoso y que les puede ayudar a minimizar bastante su tiempo y código necesario.

Si bien, en el curso usamos la versión [3.3.7](https://getbootstrap.com/docs/3.3/), la última versión es la [4.0](https://getbootstrap.com/). Aún van a encontrar muchos ejemplos en la versión 3.x, la versión 4.0 todavía no es muy utilizada.

Para asegurarse que la biblioteca está funcionando efectivamente, recuerden las etiquetas en el head
```html
<meta http-equiv="X-UA-Compatible" content="IE=edge">
<meta name="viewport" content="width=device-width, initial-scale=1">
```

¿Lo que siempre tienen que recordar y practicar de Bootstrap? El sistema de **Grid** y los **Containers** (`container` y `container-fluid`).

### Grid System
Con Bootstrap podíamos especificar la cantidad de unidades que estaría ocupando nuestra columna, dentro de nuesta fila de 12 unidades. Para ver el material completo, siempre es recomendable leer la [documentación](https://getbootstrap.com/docs/3.3/css/#grid).
```html
<!-- Ejemplo de 12 columnas de 1 unidad, en pantalla mediana -->
<div class="row">
   <div class="col-md-1"></div>
   <div class="col-md-1"></div>
   <div class="col-md-1"></div>
   <div class="col-md-1"></div>
   <div class="col-md-1"></div>
   <div class="col-md-1"></div>
   <div class="col-md-1"></div>
   <div class="col-md-1"></div>
   <div class="col-md-1"></div>
   <div class="col-md-1"></div>
   <div class="col-md-1"></div>
   <div class="col-md-1"></div>
</div>

<!-- Ejemplo de dos columnas que ocupan 50% cada una, en pantallas medianas y 100% en pantallas pequeñas -->
<div class="row">
   <div class="col-md-6 col-sm-12"></div>
   <div class="col-md-6 col-sm-12"></div>
</div>
```
### Algunos links de referencia

- https://getbootstrap.com/ \- Sitio Web oficial de Bootstrap;
    
- https://startbootstrap.com/ \- Algunos templates gratuitos;
    
-   https://www.bootstrapcdn.com/ \- CDN recomendado;
-   http://fontawesome.io/ \- Herramienta extra (**PROBAR PARA SABER**);


