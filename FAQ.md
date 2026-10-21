# CSV Guard — preguntas frecuentes

Última actualización: 2026-10-19. Aplica a la versión 0.1.0.

## ¿Qué hace CSV Guard?

Revisa un archivo CSV y señala riesgos frecuentes antes de importarlo: filas con distinto número de columnas, cabeceras vacías o duplicadas, posibles fórmulas de hoja de cálculo, fechas y números ambiguos, ceros iniciales, identificadores largos y duplicados en columnas de ID.

## ¿Corrige el archivo?

No. Solo informa de incidencias. Conserva una copia del original y decide cada cambio antes de importar.

## ¿Sube el CSV a Internet?

La aplicación 0.1.0 no incorpora backend, telemetría ni almacenamiento persistente. El análisis se ejecuta en el navegador. El proveedor que aloje la landing o la descarga puede registrar la IP y datos técnicos bajo sus propias condiciones; esto no implica que reciba el contenido del CSV.

## ¿Necesito crear una cuenta?

No para usar CSV Guard. La descarga inicial es pública y gratuita.

## ¿Qué requisitos y límites tiene?

- Navegador moderno y servidor HTTP local; no se recomienda abrir el HTML mediante `file://`.
- Archivos de hasta 5 MiB.
- Coma como delimitador.
- Detección acotada: puede haber falsos positivos y omisiones.

El README incluido explica la ejecución local.

## ¿Cómo compruebo la descarga?

Descarga también el manifiesto `csv-guard-0.1.0.SHA256SUMS.txt`. SHA-256 permite comprobar integridad, pero no acredita autoría ni elimina la necesidad de obtener el paquete desde la URL publicada.

## ¿Qué licencia tiene?

El código propio se distribuye bajo licencia MIT. Los componentes de terceros conservan sus licencias, recogidas en `THIRD_PARTY_NOTICES.md`.

## ¿Es gratis? ¿Habrá una versión de pago?

La evaluación 0.1.0 es gratuita y no tiene checkout activo. Un pago único de 19 EUR es solo una hipótesis futura; no existe venta hasta completar la configuración legal y de cobro.

## ¿Puedo enviar mi CSV para soporte?

No. No envíes CSV, fragmentos de datos, nombres de personas ni información confidencial. Puedes describir un patrón con un ejemplo totalmente sintético.

## ¿Cómo doy feedback?

Es opcional. Escribe a open.boro@gmail.com indicando únicamente: si pudiste ejecutarlo, si detectó algo útil y si considerarías un pago único de 19 EUR. El correo revela tu dirección al proveedor y al destinatario.

## ¿CSV Guard garantiza una importación segura?

No. No detecta todos los riesgos ni sustituye copias de seguridad, revisión humana o controles del sistema de destino. No debe ser la única salvaguarda para decisiones críticas.
