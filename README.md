# Reporte integrado de prensa 2026

Reporte de prensa, alcance y difusión de la agenda cinematográfica de FUNGLODE, Festival de Cine Global Santo Domingo y GFDD / GFDD-Florida, con actividades en Miami y Nueva York. Corte del documento: 29 de septiembre de 2026.

**Preparado por ODLC.**

## Crear el nuevo repositorio

Nombre sugerido: `REPORTE-INTEGRADO-DE-PRENSA-2026`

Descripción para GitHub:

> Reporte integrado de prensa, alcance y difusión de la agenda cinematográfica FUNGLODE / FCGSD / GFDD en Miami y Nueva York. Julio–septiembre de 2026.

Crea este repositorio separado de la relatoría de Filadelfia. Si lo alojas en FUNGLODEFILMS, selecciona esa organización como Owner al crearlo.

## Subir y publicar

1. Descomprime el ZIP.
2. Abre la carpeta `REPORTE-INTEGRADO-DE-PRENSA-2026`.
3. En el nuevo repositorio vacío, pulsa **uploading an existing file**. Si ya contiene archivos, utiliza **Add file → Upload files**.
4. Arrastra **el contenido de la carpeta**, incluyendo `index.html`, `assets`, `documentos` y `README.md`. No subas el ZIP ni la carpeta principal completa. El archivo `index.html` debe quedar en la raíz.
5. Guarda con **Commit changes** en `main`.
6. Añade `.nojekyll` si no se cargó: **Add file → Create new file**, nombre `.nojekyll`, contenido `# Sitio estático`, y guarda en `main`.
7. En **Settings → Pages**, selecciona **Deploy from a branch**, **main**, **/(root)** y **Save**.
8. Abre la dirección que muestre GitHub al terminar el despliegue.

Guía oficial: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Estructura

```text
index.html
assets/
  recortes/
    image1.jpeg … image12.jpeg
documentos/
  reporte-integrado-de-prensa.docx
README.md
.nojekyll
```

El diseño y las funciones están incluidos en `index.html`; no hace falta instalar ni compilar nada. Las imágenes y el documento descargable son archivos locales y deben subirse también. Se puede revisar el sitio abriendo `index.html` directamente en un navegador.

## Contenido y funcionamiento

- Portada ejecutiva, indicadores y distribución mensual de las publicaciones.
- 24 secciones que conservan el contenido sustantivo del reporte.
- 100 entradas del anexo: 98 registros documentales y 2 referencias complementarias de redes y video. Estas últimas no se suman al indicador de publicaciones.
- Búsqueda por medio, titular, fecha o texto del registro y filtro por tipo.
- 12 imágenes originales extraídas del documento, con pies de imagen y visor ampliable.
- Descarga del Word original, sin modificaciones.
- Crédito «Preparado por ODLC».
- Párrafos justificados en pantallas amplias y papel; alineados a la izquierda en móvil.
- Impresión/PDF que incluye todos los registros aunque haya un filtro activo en pantalla.
- Contenido y enlaces accesibles sin JavaScript; las imágenes se abren directamente en ese caso.
- Metadatos de título, descripción, idioma y Open Graph.

No incluye seguimiento, cookies, bibliotecas remotas ni tipografías externas. Los enlaces de prensa son los suministrados en el documento; no se rellenaron los enlaces ausentes ni se verificó nuevamente la disponibilidad de cada página externa.

## Fuente y cifras

La fuente es `REPORTE INTEGRADO DE PRENSA.docx`, aportado por el usuario. El sitio conserva el texto del informe, sus enlaces, los registros y los recortes. Los encabezados se adaptaron para facilitar la navegación, y se añadieron controles de consulta y un gráfico de las cifras mensuales expresadas en el documento.

Las cifras de 93 publicaciones, 98 registros y 56 URL son las declaradas en el reporte, no una nueva auditoría de medios ni una estimación de audiencia. La metodología y las diferencias entre fuentes se conservan dentro del informe.

El documento presenta una diferencia en el pico del 7 de septiembre: 13 publicaciones en indicadores generales y 12 en el balance de difusión. Se mantienen ambas redacciones en sus respectivas secciones, sin elegir una cifra arbitraria ni usarla para una gráfica de picos. El anexo conserva asimismo las diferencias de fecha y atribución entre fuentes. El período general inicia el 22 de julio; el criterio ampliado incluye una mención impresa del 2 de julio.

El archivo visual contiene las 12 imágenes suministradas: incluye una captura de elsureño.net que el documento excluye del registro consolidado. Por eso el número de imágenes no debe interpretarse como una correspondencia uno a uno con las 12 publicaciones impresas.

## Cambios posteriores

Para corregir textos, edita `index.html` en GitHub con el lápiz y guarda con **Commit changes**. Mantén las etiquetas HTML. Para cambiar estilos, modifica el bloque `<style>`; las funciones están en el bloque `<script>` al final.

Al disponer del enlace público definitivo, puedes añadir dentro de `<head>` las etiquetas `canonical` y `og:url` con esa dirección. No se ha supuesto una dirección definitiva ni añadido una imagen promocional que el usuario no haya proporcionado.

Para guardar un PDF, pulsa **Imprimir / PDF**, selecciona A4 y **Guardar como PDF**. Desactiva los encabezados y pies automáticos del navegador si deseas una presentación más limpia.
