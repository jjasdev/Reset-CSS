# Reset CSS

Esta hoja de estilos servirá para eliminar el formato original de los navegadores en tus proyectos.

## ¿Qué es?

Cada navegador tiene su presentación por defecto y este comportamiento individualizado puede generar conflictos de diseño frente a tu proyecto web.

Aunque todos coinciden en algunos valores importantes (tipo de letra serif, color de letra negro, etc.) presentan diferencias en valores tan importantes como los márgenes verticales `margin-bottom` y `margin-top` de los títulos de sección `h1`,… `h6`, la tabulación izquierda de los elementos de las listas `margin-left` o `padding-left` según el navegador y el tamaño de línea del texto `line-height`, entre otros.

La técnica de **reset CSS** es una forma de suavizar estas diferencias y estandarizar el estilo superponiendo el formato original del navegador con una hoja de estilo. Por lo tanto, **reset CSS** se ha convertido en un archivo casi obligatorio en todos los proyectos web que existen, su uso hará que el aspecto de nuestro diseño se vea más igualado entre los navegadores, lo que facilitará el tener una buena experiencia de usuario.

## ¿Cómo usarlo?

Antes de comenzar a estilizar el proyecto, el código del archivo **reset CSS** deberá haber sido agregado para que se elimine el formato original de los navegadores. Al ser una hoja de estilo podremos usarla como normalmente usamos las hojas de estilo en un proyecto web:

-	Al inicio del archivo CSS
-	En un archivo externo. Para ello, en el archivo HTML, dentro de la tag `head`, usaremos la tag `link` para llamar al archivo
```html
<link rel="stylesheet" href="reset.css">
``` 

Con el **reset CSS** agregado al proyecto, se podrán aplicar ya el resto estilos de diseño.