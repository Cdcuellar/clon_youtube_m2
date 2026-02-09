# Analisis de Implementacion Estructural - Version Gemini 1.5 Pro

# [youtube clon m2]()

Este documento detalla el desarrollo de la replica de YouTube utilizando exclusivamente estandares de HTML5 semantico, omitiendo cualquier tecnologia de estilos o programacion externa.

## Modelo usado
Gemini 1.5

## Arquitectura del Proyecto
La version desarrollada por este modelo se enfoca en la organizacion espacial y la jerarquia de contenidos, utilizando elementos estructurales para suplir la ausencia de CSS.

### Especificaciones de Etiquetas Utilizadas:
- Estructura de Bloque: Se implementaron las etiquetas &lt;header&gt; para la cabecera, &lt;main&gt; para el cuerpo central, &lt;aside&gt; para el menu lateral y &lt;footer&gt; para el cierre del sitio.
- Maquetacion: Se utilizo la etiqueta &lt;table&gt; con atributos de ancho y alineacion para organizar la interfaz en tres columnas funcionales.
- Interactividad Nativa: Se aprovecho el elemento &lt;details&gt; junto con &lt;summary&gt; para crear secciones desplegables en las descripciones de los videos.
- Multimedia: Los videos se integraron mediante &lt;iframe&gt;, configurando parametros de reproduccion desde la URL.
- Navegacion: Uso de etiquetas &lt;nav&gt; con listas desordenadas &lt;ul&gt; y enlaces internos &lt;a href="#id"&gt; para permitir el desplazamiento dentro del mismo documento.

## Metadatos y Configuracion
En el sector &lt;head&gt; se incluyeron las etiquetas &lt;meta&gt; obligatorias para la codificacion UTF-8 y la adaptabilidad del viewport, asegurando que la estructura sea legible en diversos dispositivos.

### Conclusion del Modelo:
Este enfoque prioriza el orden visual y la experiencia de usuario dentro de las limitaciones de HTML puro, logrando una distribucion de contenidos que recuerda fielmente a la plataforma original.
