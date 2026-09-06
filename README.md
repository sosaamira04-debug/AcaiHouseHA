# Açaí House H&A — Proyecto Android

Proyecto Android nativo que empaqueta la primera versión de la caja como una app offline.

## Funciones
- Açaí tradicionales y especiales.
- Agregados a G. 3.000.
- Helados cargados, en icopor y variados.
- Efectivo, transferencia, tarjeta y QR.
- Cálculo de total, dinero recibido y vuelto.
- Historial de ventas.
- Caja del día.
- Catálogo de precios.
- Guardado local de ventas.

## Generar el APK
En Android Studio: abrir el proyecto, sincronizar Gradle y usar
Build > Build APK(s).

También incluye un workflow de GitHub Actions para generar un APK
debug en la nube.

## Datos
Las ventas se guardan localmente en el dispositivo. En una próxima
versión conviene agregar exportación/importación de respaldo y/o
sincronización en la nube para evitar pérdidas al cambiar de teléfono.
