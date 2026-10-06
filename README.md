# CASA VERDE POS — PWA gratuita

## Modelo actual

Esta versión está preparada para publicarse gratis en **GitHub Pages**. Las transacciones se guardan en el almacenamiento local del navegador del dispositivo y pueden consultarse por **año, mes, salón y método de pago**.

Incluye los métodos de cobro:

- QR
- Efectivo
- Tarjeta
- Transferencia

El cobro siempre permite elegir **OK · Confirmar cobro** o **Cancelar**. Cancelar cierra la ventana sin registrar la venta.

## Productos incorporados

- Menú de almuerzo — Bs 90.
- Queso a la carta — nombre y precio editables al agregarlo.
- Botella de vino a la carta — nombre y precio editables al agregarla.
- Cóctel a la carta — nombre y precio editables al agregarlo.
- Bebida a la carta — nombre y precio editables al agregarla.

## Publicar en GitHub Pages

1. Crea un repositorio nuevo en GitHub.
2. Sube todos los archivos de esta carpeta manteniendo la estructura.
3. Ve a **Settings → Pages**.
4. Selecciona **Deploy from a branch**.
5. Elige la rama `main` y la carpeta `/root`.
6. Guarda y espera a que GitHub publique la página.

## Historial y respaldo

En **Ventas / Reportes** se puede seleccionar año y mes; por ejemplo, año 2026 y diciembre. El historial permanece en el navegador mientras no se borren sus datos.

Usa con frecuencia el botón **Respaldo** para descargar el JSON. Guarda varias copias fuera del teléfono o computadora.

> Importante: GitHub Pages publica la aplicación, pero no ofrece una base de datos. Esta versión gratuita conserva las ventas en el dispositivo donde se usa. Si después se necesita trabajar desde varios dispositivos o tener una base central, habrá que conectar una base de datos externa, por ejemplo Supabase, sin cambiar la interfaz principal.

## Instalar en el celular

- Android: abre la URL en Chrome y selecciona **Instalar aplicación** o **Agregar a pantalla de inicio**.
- iPhone: abre la URL en Safari y usa **Compartir → Añadir a pantalla de inicio**.
