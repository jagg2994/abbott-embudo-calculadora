# Embudo de calculadora muscular

Dashboard estático de GitHub Pages. Muestra el embudo móvil por país y la adquisición por canal o fuente/medio.

## Actualización de datos

1. Ejecutar `refreshMac2FunnelReport()` en el Apps Script vinculado a la hoja.
2. Desde el repositorio privado, ejecutar `node tools/build-mac-funnel-dashboard-data.mjs`.
3. Publicar solo `index.html`, `data/funnel-data.json`, `.nojekyll` y este README.

La pestaña `MAC 2.0 - Funnel por fuente 3M` habilita que canal y fuente/medio filtren el embudo. Mientras falte, esos filtros describen adquisición únicamente.
