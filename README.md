# La palabra del día

Juego de palabras progresivo (estilo Wordle), con solución fija **VIAJE** y seis intentos.

## Archivos
- `index.html`: juego adaptable a móviles y tabletas.
- `manifest.webmanifest`: nombre, iconos y modo de aplicación.
- `sw.js`: caché para poder abrir el juego sin conexión tras la primera visita.
- `icons/`: iconos para Android y Apple.

El progreso se guarda localmente en el dispositivo.

## Publicar con GitHub Pages
1. Abre **Settings → Pages** en este repositorio.
2. En **Build and deployment**, selecciona **Deploy from a branch**.
3. Elige la rama **main** y la carpeta **/(root)**.
4. Pulsa **Save** y espera a que finalice la publicación.

La dirección será: https://ffdg21.github.io/la-palabra-del-dia/

## Instalar
- **Android:** abre el enlace con Chrome, pulsa ⋮ y elige **Instalar aplicación** o **Añadir a pantalla de inicio**.
- **iPhone/iPad:** abre el enlace con Safari, pulsa **Compartir → Añadir a pantalla de inicio**.

La aplicación necesita HTTPS para instalarse. Después de la primera visita con conexión, el juego puede funcionar sin conexión gracias al service worker.

El repositorio es público; el código y la solución VIAJE serán visibles para quien lo visite.