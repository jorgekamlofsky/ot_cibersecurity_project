# Sitio Ciberseguridad OT — UAI / CAETI

Primera versión del rediseño mobile-first.

## Estructura

- `index.html` — sitio principal single-page con anclas internas.
- `produccion-cientifica.html` — página independiente para publicaciones.
- `css/styles.css` — estilos responsive.
- `js/main.js` — menú, acordeones y visor de imágenes.
- `imagenes/` — colocar aquí las imágenes indicadas.
- `papers/` — colocar aquí los PDF de publicaciones.

## Imágenes esperadas

Colocar en `imagenes/`:

- `logo-uai.png` (ya disponible)
- `arquitectura_purdue_ot.png`
- `analisis_alertas_cisa.png`
- `laboratorio_modbus_plc.jpg`
- `forensia_en_vivo.png`
- `ciberdefensa_desplegable.jpg`

No se utiliza `red_ot_background`.

## PDFs esperados

La página de producción científica referencia inicialmente:

- `papers/kamlofsky_conaiisi_2015.pdf`
- `papers/ciberdefensa_infraestructuras_industriales_2015.pdf`
- `papers/guia_incidentes_infraestructuras_criticas_2021.pdf`

Si los nombres reales son diferentes, modificar los `href` en `produccion-cientifica.html`.

## Publicación

Subir todo el contenido del proyecto al repositorio de GitHub Pages, manteniendo las carpetas `imagenes/`, `css/`, `js/` y `papers/`.

La web no requiere servidor ni base de datos.
