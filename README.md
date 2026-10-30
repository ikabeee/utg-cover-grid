# Portadas del UTG Game Showcase

Plantilla y guía para hacer la portada de tu videojuego para el sitio del evento. Diseñas **una sola imagen de 1920×1080** y la página te da la tarjeta y el coverflow ya recortados y con su nombre.

> **Urgen la tarjeta y el coverflow.** Súbelos primero al Drive del evento.

## Empieza aquí

1. Descarga este repo: botón verde **Code → Download ZIP** y descomprímelo (o `git clone`).
2. Abre `index.html` con doble clic. Se abre en tu navegador, no necesitas instalar nada ni internet.
3. En **Descarga la plantilla**, baja el SVG (Figma, Illustrator, Inkscape, Affinity, Penpot) o el PNG de guías (Photoshop, Krita, Procreate, Canva).
4. Diseña tu portada en tu herramienta siguiendo la **Guía de uso** de la página.
5. En **Prueba tu portada**, súbela, escribe el nombre de tu juego y descarga `[slug]-tarjeta.jpg` y `[slug]-coverflow.jpg`.
6. Súbelos a tu carpeta `[slug]/` en el [Drive del evento](https://drive.google.com/drive/folders/1ZsImnvoS70XPs6qN1ERIHSv1_uTqbvK2), junto con las capturas de la galería (obligatorias).

Todo pasa en tu navegador: tu imagen no se sube a ningún lado.

## No uses ChatGPT ni generadores de imágenes

El arte sale de **tu juego**: capturas, sprites, modelos y logo. Si quieres ayuda de un agente, conéctalo por MCP a tu herramienta de diseño (Affinity, Penpot, Blender o Krita). La página trae los tutoriales y el paso a paso en Blender si tu juego es 3D. El prompt para tu agente está en la página y en [`PROMPT.md`](PROMPT.md).

## Medidas

| Archivo | Medidas | Prioridad |
|---|---|---|
| `[slug]-tarjeta.jpg` | 810×1080 (3:4) | Urgente |
| `[slug]-coverflow.jpg` | 794×1080, sin el nombre del juego (el sitio lo pone) | Urgente |
| `[slug]-portada.jpg` | 1920×1080 | Después |
| `[slug]-captura-01.jpg`, `-02`… | 1920×1080, galería de la ficha del juego | Obligatoria |

- Lienzo: 1920×1080 px, sRGB, JPG.
- Zona segura (personaje y título): de x=620 a x=1300 y de y=200 a y=880.
- Título: entre y=200 y y=620. Nada de texto abajo de y=620.
- `[slug]`: el nombre del juego en minúsculas, sin acentos y con guiones. "Los Últimos Faros" → `los-ultimos-faros`. La página lo arma por ti.

## Qué hay en el repo

| Archivo | Para qué |
|---|---|
| `index.html` | La guía completa, las descargas y la prueba de recortes. |
| `template/utg-portada-plantilla.svg` | Plantilla con capas `arte` y `guias`. |
| `template/utg-portada-guias.png` | Sólo las guías, fondo transparente. |
| `PROMPT.md` | Prompt para tu agente conectado por MCP. |

Si un botón de descarga no responde, toma los archivos directo de la carpeta `template/`.
