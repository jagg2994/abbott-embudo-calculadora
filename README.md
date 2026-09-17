# Growth Tool — Sankey de conversión

Dashboard estático de GitHub Pages para los 13 países de Growth Tool. Muestra el canal de adquisición, los pasos medidos del flujo, la distribución de resultados rojo/amarillo/verde y la presencia del evento `registro_exitoso`.

## Actualización de datos

1. Ejecutar `refreshGrowthToolFunnelSankey()` en el Apps Script vinculado al Google Sheet.
2. Desde el repositorio privado, ejecutar `node tools/build-growth-tool-sankey-data.mjs`.
3. Publicar únicamente `index.html`, `data/growth-funnel-data.json`, `.nojekyll` y este README.

Los datos son agregados por país, canal y evento; no incluyen identificadores personales. El registro exitoso no se atribuye a un color de resultado hasta que el evento incluya también el parámetro `result`.
