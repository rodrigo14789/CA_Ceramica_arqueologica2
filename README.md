# ARQUEODEX · Cerámica arqueológica

Aplicación web instalable para registrar cerámica en Android. Guarda fichas y fotografías en IndexedDB dentro del almacenamiento local del navegador. Incluye siete secciones con colores, contraseña local, panel para editar nombres y opciones y bloquear campos, inventario, estadísticas, respaldo JSON y exportación Excel `.xlsx`.

## Instalar en Android

Publica los archivos de esta carpeta mediante HTTPS, por ejemplo con GitHub Pages. En Chrome para Android abre la página y utiliza el menú para añadirla a la pantalla de inicio o instalarla. Tras la primera carga completa, puede abrirse sin conexión. Conserva siempre la misma dirección para acceder al mismo inventario.

El botón Descargar Excel exporta todas las fichas a ARQUEODEX.xlsx. El navegador gestiona la descarga al dispositivo. Las fotos completas se incluyen en Exportar respaldo, mientras que Excel incluye sus nombres. Importar respaldo permite recuperar las fichas que falten.

## Almacenamiento

Los datos pertenecen al navegador y dispositivo utilizados. Borrar los datos del sitio elimina el inventario local. Guarda respaldos JSON para recuperarlo. La contraseña bloquea la interfaz y se almacena como hash local, sin cifrar la base de datos. Los nombres editados y los bloqueos de campos se conservan en ese navegador.

Esta entrega es una aplicación web instalable. La integración con el almacenamiento y las descargas debe comprobarse en el dispositivo Android utilizado. La validación automatizada cubre persistencia tras recarga, configuración y bloqueo de campos, contraseña y contenido del archivo XLSX.

JSZip está incluido localmente con su licencia en la cabecera de jszip.min.js y permite crear Excel sin servicios externos.
