# Post Atlas · Biblioteca de referencias

Galería de posteos y feeds, con lienzo de zoom/paneo, filtros y selección, adaptable a teléfonos y computadoras.

## Publicación

La interfaz está en [index.html](./index.html), sin dependencias ni compilación. Para habilitar su URL pública: **Settings → Pages → Build and deployment → Source: GitHub Actions**. El flujo [pages.yml](./.github/workflows/pages.yml) publica los cambios de `main`.

## Archivos pendientes de importar

El visor se publicó con **75 referencias catalogadas**, pero la conexión con GitHub disponible en este chat no permite subir automáticamente el ZIP binario de las fotos. Los dibujos mostrados como sustitutos son explícitamente provisionales, no las imágenes históricas. **No están subidos los PNG originales, los 75 WebP de miniaturas ni el ZIP de la última versión (240 feeds / 2.160 posteos)**. No se deben afirmar disponibles hasta que esos recursos estén realmente en el repositorio.

Para completar la importación, extraer `Lienzo_Biblioteca_Posteos_Todos_Los_Nichos.zip` y subir el contenido de `Biblioteca_Posteos/assets/` a `assets/` en el repo. Las miniaturas tienen los nombres numéricos `001.webp` a `075.webp` y deberían verse automáticamente. Las rutas de los originales deben ajustarse de acuerdo con `Biblioteca_Posteos/data.js`, que incluye los nombres completos.

## Controles

- Mobile: menú ☰ por nicho, pestañas de posteos/feeds, pellizcar para acercar, desplazar arrastrando, selector de piezas.
- Desktop: rueda para zoom, arrastrar lienzo, búsqueda, y controles + / −.

**Estado actual:** interfaz funcional con referencias de reemplazo; no biblioteca fotográfica completa.
