# Mis finanzas

App personal de finanzas en un solo archivo (`index.html`). Funciona en el navegador y se instala en el teléfono como app.

- Gastos, ingresos y pagos de tarjeta; sueldo semanal, quincenal o mensual.
- Topes semanales, lista de espera de 48 h, recurrentes y compras a meses (MSI).
- Tarjetas de crédito con deuda, corte y fecha límite; cuentas con rendimiento anual.
- Análisis: revisión semanal, Pareto, tendencia, proyección y más.

## Privacidad

Los datos **no** se guardan en este repositorio ni en ningún servidor: viven solo en el navegador de cada dispositivo (`localStorage`). Usa **Ajustes → Datos → Descargar respaldo** con frecuencia y **nunca subas los archivos de respaldo** aquí.

## Publicar con GitHub Pages

1. Sube estos archivos a la raíz del repositorio (rama `main`).
2. En **Settings → Pages**: *Source* = *Deploy from a branch*, rama `main`, carpeta `/ (root)`.
3. La app queda en `https://<tu-usuario>.github.io/<repo>/`.

Para actualizar, reemplaza `index.html` y haz commit; al abrir la app con internet se descarga la versión nueva. Si cambias `sw.js`, sube también el número de `CACHE`.
