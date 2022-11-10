# Archivos de ejemplo para "Introducción al procesamiento de imágenes"

La selva amazónica es la selva más grande y biodiversa del mundo, así que es muy importante protegerla. 

Desafortunadamente, la deforestación ha causado un impacto profundo en áreas de conservación. Esto está directamente conectado a daños que aceleran el cambio climático. 

Aprenda cómo usar el Image Processing Toolbox (procesamiento de imágenes) para analizar y cuantificar la deforestación en la selva amazónica. Puede usar como referencia el video del canal de YouTube MATLAB en Español ("Introducción al procesamiento de imágenes para análisis de cambio climático con MATLAB"):

https://youtu.be/ZZ-XPZcCvCQ

El Live Script deforestacion.mlx procesa múltiples imágenes satelitales del Bosque Nacional Jamanxim tomadas cada 4 años desde 2000 hasta 2016.

Explore el script createMask.m - una función exportada desde el Color Thresholder App que permite convertir la experiencia interactiva con el app en código que se puede usar. 

Ejecute el Live Script (todo o por secciones) y observe los resultados. Puede editar partes del algoritmo y encontrar formas de mejorar el resultado. 

Para empezar, intente regenerando la función createMask.m con diferentes valores umbrales o usando un espacio de colores diferente en el Color Thresholder App.

