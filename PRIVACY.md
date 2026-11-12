# Política de privacidad — HLS Stream Detector

_Última actualización: 2026-11-09_ · [English below](#privacy-policy--hls-stream-detector)

HLS Stream Detector procesa todo **dentro de tu navegador**. No tenemos servidores: no recogemos, no enviamos, no vendemos ni compartimos datos con nadie.

## Qué datos usa y para qué

| Dato | Para qué | Dónde se guarda | Cuánto tiempo |
|---|---|---|---|
| URLs y tipo de contenido de las peticiones de red de la pestaña (solo se conservan manifiestos `.m3u8`/`.mpd` y archivos multimedia) | Detectar el video que estás viendo | Memoria del navegador | Hasta que cambias de página o cierras la pestaña |
| Título de la página y URLs de imágenes visibles (póster, `og:image`) | Proponer el nombre del archivo y la miniatura | Memoria del navegador | Mientras el popup está abierto |
| URL del playlist del video que descargas | Reanudar la descarga si el navegador se cierra | IndexedDB local | Se borra al guardar el archivo, al cancelar o como máximo 24 h después de terminar |
| Partes del video descargado | Construir el archivo final | Almacenamiento privado del navegador (OPFS) | Igual que la fila anterior |
| Historial local de descargas (nombre de archivo, dominio, tamaño, fecha, estado) | Evitar duplicados y registrar el resultado | IndexedDB local | Hasta que desinstalas la extensión |
| Fecha en que aceptaste el aviso de uso | No volver a mostrarlo | `chrome.storage.local` | Hasta que desinstalas la extensión |

Los segmentos del video se piden directamente a los mismos servidores de los que procede el video que estás viendo. El navegador hace esas peticiones igual que las haría la propia página (con las cookies de ese sitio); la extensión no las lee ni las modifica. Ningún dato pasa por servidores nuestros ni de terceros.

## Lo que no hace

- No usa analítica, publicidad ni rastreadores.
- No lee ni modifica cookies, credenciales, User-Agent ni Referer.
- No automatiza clics ni controla el reproductor.
- No descarga videos de YouTube ni elude DRM o protecciones anticopia.

## Diagnóstico

Si una descarga falla puedes pulsar «Copiar diagnóstico». Solo copia al portapapeles el estado del error, la versión y el dominio y la ruta del playlist, nunca la URL completa con tokens. No se envía a ningún sitio: tú decides si lo compartes.

## Borrar tus datos

Al desinstalar la extensión, Chrome elimina todos sus datos locales.

## Contacto

d4v1d1126@gmail.com

---

# Privacy Policy — HLS Stream Detector

_Last updated: 2026-11-09_

HLS Stream Detector processes everything **inside your browser**. We have no servers: we do not collect, transmit, sell or share any data with anyone.

## What data it uses and why

| Data | Purpose | Where it is stored | How long |
|---|---|---|---|
| URLs and content type of the tab's network requests (only `.m3u8`/`.mpd` manifests and media files are kept) | Detect the video you are watching | Browser memory | Until you leave the page or close the tab |
| Page title and URLs of visible images (poster, `og:image`) | Suggest a file name and a thumbnail | Browser memory | While the popup is open |
| Playlist URL of the video you download | Resume the download if the browser closes | Local IndexedDB | Deleted when the file is saved, when you cancel, or at most 24 h after it finishes |
| Downloaded video parts | Build the final file | Browser private storage (OPFS) | Same as the row above |
| Local download history (file name, domain, size, date, status) | Avoid duplicates and record the result | Local IndexedDB | Until you uninstall the extension |
| Date you accepted the usage notice | Not show it again | `chrome.storage.local` | Until you uninstall the extension |

Video segments are requested directly from the same servers that serve the video you are watching. The browser makes those requests just as the page itself would (with that site's cookies); the extension does not read or change them. No data goes through our servers or any third party.

## What it does not do

- No analytics, advertising or trackers.
- It does not read or change cookies, credentials, User-Agent or Referer.
- It does not automate clicks or control the player.
- It does not download YouTube videos or bypass DRM or copy protection.

## Diagnostics

If a download fails you can press "Copy diagnostics". It only copies the error status, the version and the playlist's domain and path to your clipboard, never the full URL with tokens. Nothing is sent anywhere: you decide whether to share it.

## Deleting your data

When you uninstall the extension, Chrome removes all of its local data.

## Contact

d4v1d1126@gmail.com
