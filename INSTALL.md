# CSV Guard 0.1.0 — instalación y retirada

CSV Guard es una aplicación web estática. El análisis ocurre en la memoria del navegador; el paquete no incorpora backend, telemetría ni almacenamiento persistente.

## Antes de abrir

1. Descarga el paquete y el manifiesto SHA-256 desde esta misma página.
2. Conserva completa la carpeta descomprimida; no separes ni renombres sus archivos internos.
3. Si quieres comprobar integridad, contrasta los archivos con `csv-guard-0.1.0.SHA256SUMS.txt`. SHA-256 detecta cambios, pero no acredita autoría.

## Abrir localmente

Requiere Node.js 22 o 24, o un servidor HTTP estático de confianza.

1. Abre una terminal dentro de la carpeta `csv-guard-0.1.0`.
2. Ejecuta `node serve-local.mjs`.
3. Abre `http://127.0.0.1:4173` en un navegador moderno.
4. Detén el servidor con `Ctrl+C` al terminar.

El servidor incluido escucha solo en `127.0.0.1`, admite GET/HEAD y no escribe archivos. No abras `index.html` mediante `file://` y no expongas la carpeta en `0.0.0.0` ni en una interfaz de red.

## Primera comprobación

- Pulsa «Usar ejemplo sintético» antes de elegir un archivo propio.
- Confirma que aparecen resumen, incidencias y filtros.
- La herramienta admite archivos `.csv` de hasta 5 MiB y coma como delimitador.
- Conserva una copia del CSV original: CSV Guard informa, no corrige ni garantiza detectar todos los problemas.

## Actualizar o volver atrás

1. Conserva la carpeta de la versión anterior.
2. Descomprime la nueva versión en otra carpeta y pruébala por separado.
3. No mezcles archivos de versiones distintas.
4. Para volver atrás, detén el servidor y ejecuta `node serve-local.mjs` desde la carpeta anterior.

## Retirar

Detén el servidor y elimina la carpeta descargada. No hay cuenta, servicio instalado, migración ni datos internos que borrar. Los CSV originales no se modifican.

## Ayuda sin compartir datos

Contacto: open.boro@gmail.com. No envíes CSV, fragmentos, nombres, empresa ni información confidencial; describe cualquier problema con un ejemplo completamente sintético.
