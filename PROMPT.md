# Prompt para tu agente

Úsalo con tu agente conectado por MCP a Affinity, Penpot, Blender o Krita. Cambia lo que está entre corchetes.

```text
Estás conectado por MCP a [HERRAMIENTA: AFFINITY, PENPOT, BLENDER O KRITA]. Ayúdame a armar la portada de mi videojuego para el UTG Game Showcase.

Juego: [NOMBRE DEL JUEGO]
Género: [GÉNERO]
De qué trata: [UNA O DOS FRASES]
Material que ya tengo: [RUTA A CAPTURAS, SPRITES, MODELOS O LOGO]

Reglas del lienzo:
- Documento de 1920×1080 px en sRGB.
- Importa utg-portada-guias.png como la capa de hasta arriba, con el nombre "guias", y bloquéala.
- Arma el arte en capas con nombre (fondo, personaje, título) usando sólo mi material. No inventes personajes ni un estilo que no tenga mi juego.
- El fondo llena el lienzo hasta los cuatro bordes, sin marcos ni barras negras.
- El personaje u objeto principal y el título van dentro de la zona segura: de x=620 a x=1300 y de y=200 a y=880.
- El título va entre y=200 y y=620. No pongas texto debajo de y=620.
- El único texto es el título del juego.

Cuando termines, muéstrame una vista del lienzo con las guías visibles y espera mi visto bueno. Después oculta "guias" y exporta [nombre-del-juego].jpg a 1920×1080.
```
