# Manual de Inducción TI — Municipalidad de Machalí

Esta carpeta contiene una página web **HTML, CSS y JavaScript**, como el proyecto original. No usa React ni otras herramientas complejas.

## Archivos

- `index.html` — **aquí editas toda la página web**. Tiene tres partes:
  - `<style>` dentro de `<head>`: colores y diseño CSS.
  - `<body>`: textos, tarjetas y secciones HTML.
  - `<script>` al final: buscador, menú móvil y zoom del organigrama.
- `logo.png` — logo tomado del manual de identidad proporcionado. Mantener su proporción y colores.
- `Organigrama-Global.drawio.svg` — archivo adicional que debes copiar desde tu repositorio actual si quieres ver el organigrama. No se incluye porque no estaba adjuntado aquí.

## Cómo modificar la página

1. Abre la carpeta en Visual Studio Code.
2. Abre `index.html`.
3. Busca el texto que quieras cambiar dentro de `<body>`.
4. Modifica los colores en `:root` dentro de `<style>`. Los colores oficiales son azul `#008aab`, naranja `#f38b00` y rojo `#d70036`.
5. Guarda con **Ctrl + S** y abre `index.html` en el navegador para revisar los cambios. También puedes instalar la extensión Live Server.

## Subir cambios a tu GitHub

1. Entra al repositorio `municipalidad` en GitHub.
2. Sube **los archivos que están dentro de esta carpeta**, no la carpeta contenedora.
3. Reemplaza el `index.html` anterior, y agrega `logo.png` en la raíz. Conserva el organigrama SVG que ya hayas subido.
4. Confirma con **Commit changes**. GitHub Pages publicará los cambios si ya está activado en `main` → `/(root)`.

## Avisos

- El manual de identidad utiliza Aalto Sans; esta versión usa fuentes alternativas porque no disponemos de los archivos autorizados de esa familia tipográfica.
- Las categorías de servicios que estaban incompletas siguen marcadas como pendientes, sin inventar información.
- Revisa los permisos institucionales antes de hacer público el contenido.
