# Plantilla LaTeX para tesis y memorias de la Universidad de Chile
Plantilla LaTeX con formato requerido por la Universidad de Chile para tesis y memorias. Con esta escribí mi tesis de magíster el año 2017 en la Facultad de Ciencias Físicas y Matemáticas, la cual se adjunta en PDF como muestra (samplethesis.pdf).

El formato incluye las secciones: Portada, Resumen de tesis en español, Resumen de tesis en inglés, Dedicatoria, Agradecimientos, Índice de contenidos, Lista de Figuras, Lista de Tablas (opcional), Capítulos, Bibliografía y Apéndices. El nombre de las secciones aparece en inglés (también figuras, tablas, etc), pero puede cambiarse a español activando la línea 32 del archivo "umemoria.cls":

> \RequirePackage[spanish, es-nolists, es-lcroman]{babel} 

La bibliografía puede incluirse a través de BibTex con el archivo "AllMyReferences.bib". Las figuras a usar deben ubicarse en la carpeta Images. En la carpeta Papers se pueden incluir los artículos en PDF a incluir en los apéndices.

El nombre de la facultad se agrega en el archivo "umemoria.cls" (línea 169), así como los detalles del abstract en inglés (línea 77). Todos los demás detalles se modifican en el archivo .tex ("tesis-uchile.tex"). Este incluye además los paquetes típicos usados en reportes científicos para ecuaciones.
