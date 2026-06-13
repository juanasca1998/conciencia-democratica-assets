# Conciencia Democrática — Assets

Mirror público de assets editoriales (headshots, covers, imágenes de artículos) de [Revista Conciencia Democrática](https://conciencia-democratica.vercel.app).

## Por qué este repo

Cuando el bucket de Vercel Blob se bloqueó por overage de bandwidth (2026-06-12), perdimos acceso temporal a 56 archivos. Este repo es la red de seguridad: cada upload al sistema se mirrorea acá automáticamente, y las URLs son servidas por jsDelivr (CDN gratis con bandwidth ilimitado).

## URLs públicas

Cualquier archivo es accesible vía:

```
https://cdn.jsdelivr.net/gh/juanasca1998/conciencia-democratica-assets@main/<path>
```

Ejemplo:
```
https://cdn.jsdelivr.net/gh/juanasca1998/conciencia-democratica-assets@main/headshots/X.webp
```

## Estructura

```
headshots/      — fotos de autores (WebP 400x400, ~25 KB c/u)
covers/         — portadas de artículos (WebP max 1800w)
article-images/ — imágenes embebidas en markdown (WebP max 1600w)
placeholders/   — assets editoriales (SVG)
```

## Licencia

Los assets editoriales son del autor original (CC BY 4.0 cuando son de la revista; otras licencias indicadas en cada archivo).

El código del CMS que los administra está en el repo principal (privado).
