# Calendario GYC Costa Rica

Calendario de actividades editable, listo para GitHub Pages.

## Archivos
- `index.html` — la app (no necesita instalar nada).
- `eventos.json` — las actividades y categorías. **Es lo único que cambia al editar.**
- `logo.png` — el logo de GYC Costa Rica (lo agregas tú). Se muestra arriba del año y como ícono de la pestaña. Si no existe, la página se ve igual, sin logo.

## Publicar
1. Sube `index.html`, `eventos.json` y `logo.png` a la raíz del repositorio.
   Usa un PNG con fondo transparente para que se vea bien sobre el azul marino. Si el logo tiene otro nombre o está en otra dirección, cámbialo en **Editar → Títulos → Logo**.
2. En GitHub: **Settings → Pages → Deploy from a branch → `main` / root**.

## Editar el calendario
1. Abre la página y toca **✎ Editar calendario** (o entra con `?editar` al final de la URL).
2. Toca un día para añadir una actividad, o una fecha de la lista para cambiarla, moverla o eliminarla.
3. Los cambios se guardan solos en tu navegador hasta que los publiques.
4. Toca **Publicar en GitHub** para guardar `eventos.json` en el repositorio. La página se actualiza en 1–2 minutos.

### Token para publicar (una sola vez)
GitHub → **Settings → Developer settings → Personal access tokens → Fine-grained tokens → Generate new token**
- Repository access: *Only select repositories* → este repositorio
- Permissions → Repository → **Contents: Read and write**

Pega el token en el diálogo de publicación. Solo se guarda en tu navegador; quien visite la página no puede editar el repositorio sin su propio token.

### Sin token
Usa **Exportar** para descargar `eventos.json` y súbelo manualmente al repositorio (Add file → Upload files).

## Añadir actividades al calendario personal
- Cada fecha de la lista tiene un botón **.ics**. Al tocarlo se descarga esa actividad sola, que se abre en Google Calendar, Outlook o el calendario del celular.
- Al tocar un día marcado aparece **Añadir a mi calendario**.
- **Añadir todo el calendario (.ics)**, al final de la columna izquierda, descarga todas las actividades juntas.
