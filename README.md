# Portadas del UTG Game Showcase

Plantilla y guía para hacer la portada de tu videojuego para el sitio del evento. Diseñas **una sola imagen de 1920×1080** y la página te da la tarjeta y la portada horizontal ya recortadas y con el nombre que usa el sitio ([UT-E3](https://github.com/ikabeee/ut-e3)).

> **Urge la tarjeta (`[slug].jpg`).** Un juego sin tarjeta no se publica, y el sitio la usa también en el coverflow. Súbela primero al Drive del evento.

## Empieza aquí

1. Descarga este repo: botón verde **Code → Download ZIP** y descomprímelo (o `git clone`).
2. Abre `index.html` con doble clic. Se abre en tu navegador, no necesitas instalar nada ni internet.
3. En **Descarga la plantilla**, baja el SVG (Figma, Illustrator, Inkscape, Affinity, Penpot) o el PNG de guías (Photoshop, Krita, Procreate, Canva).
4. Diseña tu portada en tu herramienta siguiendo la **Guía de uso** de la página.
5. En **Prueba tu portada**, súbela, escribe el nombre de tu juego y descarga `[slug].jpg` (tarjeta 3:4) y `[slug]-portada.jpg` (horizontal 16:9).
6. En **Galería de capturas**, sube tus capturas del juego y descárgalas como `[slug]-captura-01.jpg`, `-02`… ya en 1920×1080.
7. Súbelo todo a tu carpeta `[slug]/` en el [Drive del evento](https://drive.google.com/drive/folders/1ZsImnvoS70XPs6qN1ERIHSv1_uTqbvK2). La galería es obligatoria.

Todo pasa en tu navegador: tu imagen no se sube a ningún lado.

## No uses ChatGPT ni generadores de imágenes

El arte sale de **tu juego**: capturas, sprites, modelos y logo. Si quieres ayuda de un agente, conéctalo por MCP a tu herramienta de diseño (Affinity, Penpot, Blender o Krita). La página trae los tutoriales y el paso a paso en Blender si tu juego es 3D. El prompt para tu agente está en la página y en [`PROMPT.md`](PROMPT.md).

## Medidas

| Archivo | Medidas | Prioridad |
|---|---|---|
| `[slug].jpg` | 810×1080 (3:4). Tarjeta del catálogo, coverflow (el sitio lo recorta a 1:1.36 y pone el nombre), miniaturas, ficha y relacionados | Urgente |
| `[slug]-portada.jpg` | 1920×1080 (16:9). Carrusel de destacados, primera imagen de la galería y vista previa al compartir | Después |
| `[slug]-captura-01.jpg`, `-02`… | 1920×1080, galería de la ficha del juego, hasta 4 | Obligatoria |

- Lienzo: 1920×1080 px, sRGB, JPG.
- Zona segura (personaje y título): de x=620 a x=1300 y de y=200 a y=880.
- Título: entre y=200 y y=620. Nada de texto abajo de y=620.
- `[slug]`: el nombre del juego en minúsculas, sin acentos y con guiones. "Los Últimos Faros" → `los-ultimos-faros`. La página lo arma por ti.

## Galería de capturas

Así se ve en la ficha del juego del sitio:

- **Visor 16:9**, recortado al centro. Si la captura no es 16:9 se pierden las orillas. En escritorio mide hasta unos 1160×652 px; en celular, todo el ancho.
- **Flechas a media altura** sobre las orillas izquierda y derecha (38 a 46 px) cuando hay más de una imagen. Deja libres unos 100 px de cada lado del lienzo de 1920.
- **Tira de miniaturas** 16:9 de 110 a 170 px de ancho, oscurecidas hasta que las seleccionas.
- **Sin texto encima**: el sitio no pone título ni pie sobre la captura.
- **Orden**: `[slug]-portada.jpg`, `[slug].jpg` y luego tus capturas por número. Se navega con flechas, deslizando o con el teclado.
- **Hasta 4 capturas**, JPG 1920×1080 sRGB. El sitio las sirve en WebP.

## Qué hay en el repo

| Archivo | Para qué |
|---|---|
| `index.html` | La guía completa, las descargas, la prueba de recortes y la galería de capturas. |
| `template/utg-portada-plantilla.svg` | Plantilla con capas `arte` y `guias`. |
| `template/utg-portada-guias.png` | Sólo las guías, fondo transparente. |
| `PROMPT.md` | Prompt para tu agente conectado por MCP. |

Si un botón de descarga no responde, toma los archivos directo de la carpeta `template/`.
