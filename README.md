# carta.celdilla.com

Sitio estático de la app «Carta del Amanecer». Se publica con GitHub Pages.

Qué hay:
- `privacidad.html`: la política de privacidad de la app. Es la misma página que la app lleva dentro. Google Play la enlaza desde la ficha.
- `cartas/`: el contenido que la app trae cada día. Hay tres archivos:
  - `indice.json`;
  - `aprobaciones.json`;
  - un `AAAA-MM-DD.json` por cada carta.

  Solo entran cartas con su aprobación y la revisión de GPT sobre su huella exacta. Las genera `herramientas/datos.py` en el repositorio de la app; aquí no se editan a mano.
- `cartas/pt/` y `cartas/fr/`: las cartas traducidas, con la misma forma. Llevan el PASS de tres familias (D-206). El inglés no está: `IDIOMAS.md` lo deja fuera de la web hasta el permiso de Cambridge (D-208).
- `index.html`: una portada sencilla, con los créditos de las Biblias de las cartas.

Qué no hay:
- datos de personas;
- cookies;
- analítica;
- código de la app.

Los envíos de «Tu opinión» y «Reportar» van a otro servicio, en Cloudflare.

Las fuentes EB Garamond y Montserrat van con su licencia OFL en `fuentes/`.
