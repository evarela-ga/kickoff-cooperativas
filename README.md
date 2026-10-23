# Kickoff Plataforma Cooperativas · GoodApps

Sitio estático (una sola página, pensada para el celular) con todo el contenido de la presentación de kickoff.

## Estructura

- `index.html`: la página completa (estilos e íconos incluidos).
- `assets/`: logos de GoodApps (azul y blanco), sin modificar.
- `.nojekyll`: indica a GitHub Pages que publique los archivos tal cual.

## Publicar en GitHub Pages

1. Crear un repositorio en GitHub (por ejemplo `kickoff-cooperativas`).
2. Subir el contenido de esta carpeta a la raíz de la rama `main`.
3. En el repositorio: **Settings → Pages → Build and deployment → Source: Deploy from a branch**, rama `main`, carpeta `/ (root)`.
4. En uno o dos minutos queda publicado en `https://<usuario-u-organización>.github.io/kickoff-cooperativas/`.

## Importante

Las páginas de GitHub Pages son públicas aunque el repositorio sea privado, salvo en planes GitHub Enterprise Cloud con acceso restringido. La página tiene `noindex` para que no aparezca en buscadores, pero cualquiera con el enlace puede verla.
