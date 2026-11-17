# Mis Gastos

App personal para registrar gastos desde el iPhone: presupuesto por categoría con avisos, seguimiento de tarjeta de crédito frente a su línea, cuotas y préstamos, metas de ahorro y dashboards del mes y del año.

Es una web app instalable (PWA): no necesita App Store, Mac ni cuenta de desarrollador. Los datos se guardan solo en el teléfono (con opción de exportar un respaldo).

## Instalar en el iPhone

1. Abre en **Safari** la dirección de GitHub Pages del repositorio.
2. Toca **Compartir** (el cuadrado con flecha) → **Añadir a pantalla de inicio** → **Añadir**.
3. Abre la app desde el nuevo ícono "Mis Gastos" (no desde Safari: son almacenamientos distintos).
4. En **Más → Ajustes** toca **Activar notificaciones** (requiere iOS 16.4 o superior).

## Archivos

- `index.html`: toda la app (HTML, CSS y JS sin dependencias).
- `sw.js`: service worker para que funcione sin internet.
- `manifest.webmanifest`, `icons/`: instalación en la pantalla de inicio.
