# RVISIOON · Parque 360

Demostración independiente de un recorrido panorámico de 18 puntos, con vistas de día y de noche, mapa y navegación entre puntos. El contenido carga progresivamente y no depende de Kuula ni de servicios externos.

## Probar

Abrir el enlace de GitHub Pages de este repositorio. Arrastrar para mirar alrededor; pulsar los círculos para avanzar o seleccionar un punto en el mapa. Los botones Día y Noche conservan la dirección de la vista.

Las 36 panorámicas se sirven en versiones de 2048×1024 y 4096×2048. Aproximadamente 66 MB en total, solicitados según se recorre el parque. Añadir `?debug=1` al enlace muestra métricas de carga para la evaluación de rendimiento.

## RV

Modo WebXR preparado para visores y navegadores compatibles. Pendiente de validación con hardware físico. Las imágenes son monoscópicas; se puede mirar alrededor y avanzar entre puntos, sin desplazamiento libre por una escena 3D.

## Licencias

Three.js 0.186.1: MIT, véase THREE-LICENSE.txt. La publicación de esta prueba no concede una licencia de reutilización sobre las panorámicas, la marca ni el código propio de RVISIOON.
