# Documentación de ClimApp

## Introducción
Esta documentación habla sobre el código HTML de la aplicación ClimApp. Corrección de enlace de archivos CSS y la importancia de la indentación en el código.

## 1. Enlace CSS Incorrecto
- **Descripción**: Se identificó que el enlace al archivo CSS no era correcto porque faltaba el nombre correcto del archivo.
- **Ubicación**: Línea 4.
- **Corrección Propuesta**: Asegurarse de que el atributo `href` en la etiqueta `<link>` contenga la ruta correcta al archivo CSS, por ejemplo:
  ```html
  <link rel="stylesheet" href="index.css" />

- Beneficio: Un enlace correcto al archivo CSS es esencial para aplicar los estilos deseados a la página, mejorando la presentación visual de la aplicación.

 ## 2. Falta de Indentación
 - **Descripción**: Se observó que faltaba indentación en varias líneas, lo que dificulta la legibilidad del código.
 - **Ubicación**: Líneas 33, 275, 276, así como en las etiquetas <main> y <body>.
 - **Corrección Propuesta**: Asegurarse de que todas las etiquetas HTML estén correctamente indentadas.
 - Beneficio: Una buena indentación mejora la legibilidad del código, facilitando su mantenimiento y comprensión por parte de otros desarrolladores.

##
La corrección del enlace CSS y la mejora de la indentación son pasos importantes para asegurar que el código HTML de ClimApp sea funcional y fácil de leer. Implementar estas mejoras
no solo optimiza la presentación de la aplicación, sino que también facilita el trabajo en equipo y el mantenimiento del código en el futuro.
