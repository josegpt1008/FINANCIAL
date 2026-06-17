# Mis Finanzas PWA

App PWA personal para presupuesto, flujo, tarjetas y metas.

## Archivos

- `index.html`
- `manifest.webmanifest`
- `service-worker.js`
- `icons/icon-192.png`
- `icons/icon-512.png`
- `.nojekyll`
- `README.md`

## Publicación en GitHub Pages

1. Crea un repositorio.
2. Sube todos los archivos de esta carpeta a la raíz.
3. Entra a `Settings > Pages`.
4. Selecciona `Deploy from a branch`.
5. Rama: `main`.
6. Carpeta: `/root`.
7. Abre la URL publicada.
8. En Android: Chrome > menú > Agregar a pantalla principal / Instalar.
9. En iPhone: Safari > Compartir > Agregar a pantalla de inicio.

## Datos

Los datos se guardan localmente en el navegador del dispositivo mediante `localStorage`.
GitHub Pages solo publica el código. No recibe los registros del usuario.

## Respaldo

Usa Exportar JSON dentro de la app para respaldar tus datos.
