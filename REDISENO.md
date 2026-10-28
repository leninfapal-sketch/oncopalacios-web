# Rediseño Oncopalacios

Paleta solicitada: azul marino y verde turquesa. Tonos propuestos: `#102d47` y `#087f83`; acento claro `#42c7be`. Todos se ajustan en las variables de `styles.css`.

La propuesta mantiene fotografías, datos de contacto, formación y contenidos médicos existentes. Añade reservas desde la portada, mapas de los consultorios, navegación por sección y un menú móvil accesible.

## Publicación y reversión

Los cambios se entregan en una rama independiente mediante una solicitud de cambios (pull request). La página publicada permanece en la versión actual hasta integrar la propuesta en `main`.

Versión original: `61dd19ca9b9bcd0d89c83e99d676440f1c08a93f`.

Antes de integrar: cerrar la solicitud descarta la propuesta sin afectar la página.

Después de integrar mediante un merge: usar **Revert** en la solicitud integrada crea otra solicitud que restaura la versión anterior. Integrar esa reversión vuelve a publicar el diseño previo, conservando el historial. Evitar sobrescribir el historial o usar un push forzado.
