# Magnetic Button Effect

![Vista previa](assets/preview.svg)

Botón magnético que responde a la proximidad del cursor y ofrece una reacción táctil alternativa.

## Características

- Fuerza y suavidad configurables.
- Retorno progresivo a reposo con `requestAnimationFrame`.
- Alternativa táctil y soporte para movimiento reducido.
- Responsive, sin librerías y listo para Netlify.
- Efecto y controles completos dentro de una sola toma.

## Demo en vivo

[magneticfx.ntdesweb.dev](https://magneticfx.ntdesweb.dev/)

## Instalación

Clona el repositorio, entra en `magnetic-button-effect` y abre `index.html`.

## Estructura del proyecto

`index.html` contiene la semántica, `style.css` el sistema visual, `capture.css` la composición de una toma, `script.js` la física y `assets/` las imágenes SVG.

## Cómo personalizarlo

Ajusta el color `--accent`, el tamaño de `.magnet` y los límites de los controles de fuerza y suavidad.

## Accesibilidad

El botón es nativo, los controles están etiquetados, el toque tiene respuesta equivalente y `prefers-reduced-motion` desactiva el desplazamiento.

## Rendimiento

Solo anima `transform`, agrupa actualizaciones con `requestAnimationFrame` y no crea nodos durante la interacción.

## Licencia y créditos

Licencia [MIT](LICENSE). Creado por [Nacho Torres](https://github.com/NachoTorresRD) para [NTDESWEB](https://www.ntdesweb.com) con [NT-SKILL SUPREME](https://github.com/NachoTorresRD/nt-skill-supreme).

[Ver en GitHub](https://github.com/NachoTorresRD/magnetic-button-effect) · [Trabajar con NTDESWEB](https://www.ntdesweb.com)
