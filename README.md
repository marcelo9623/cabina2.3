# EMEVE PHOTOBOOTH v3.6

Proyecto separado en HTML, CSS y JavaScript, sin bibliotecas externas ni conexión a servicios externos.

## Archivos
- `index.html`: estructura de la aplicación.
- `css/style.css`: estilos y diseño adaptable.
- `js/app.js`: funcionamiento de la cámara, sesión, plantillas y captura.
- `manifest.webmanifest`: configuración para instalar como aplicación web.
- `sw.js`: caché para poder abrir la aplicación sin conexión después de la primera carga.

## GitHub Pages
1. Sube todos los archivos y carpetas al repositorio conservando esta estructura.
2. En GitHub, abre **Settings → Pages**.
3. Selecciona la rama principal y la carpeta `/ (root)` como fuente.
4. Abre la URL HTTPS publicada y acepta los permisos de cámara.
5. Para usar sin internet, abre la aplicación al menos una vez mientras tengas conexión. El navegador debe permitir el almacenamiento sin conexión.

## Uso local
Puedes abrir `index.html` sin conexión para revisar la interfaz. Por seguridad, muchos navegadores bloquean la cámara cuando una página se abre como `file://`. Para usar la cámara sin internet, ejecútala desde un servidor local (`localhost`) o desde una instalación PWA que ya haya sido cargada y almacenada en caché.

La impresión y la conexión con cámaras Canon dependen del navegador, el sistema operativo y los controladores disponibles.
