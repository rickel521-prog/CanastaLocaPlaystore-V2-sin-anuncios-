# Canasta Loca: cómo obtener tu APK

1. Crea una cuenta gratis en github.com (si no tienes una).
2. Crea un repositorio nuevo (puede ser privado), por ejemplo "canasta-loca".
3. Sube TODO el contenido de esta carpeta al repositorio. Incluye la carpeta
   oculta ".github". En la web: "Add file" > "Upload files" y arrastra los archivos.
   Si la carpeta oculta no se sube desde el navegador, usa GitHub Desktop o git.
4. Entra a la pestaña "Actions". El flujo "Construir APK" arranca solo
   (si no, elígelo y pulsa "Run workflow"). Tarda unos 5 a 8 minutos.
5. Cuando termine con la palomita verde, abre esa ejecución y baja a "Artifacts":
   descarga "canasta-loca-apk" (un .zip con app-debug.apk adentro).
6. Pasa el APK a tu Android e instálalo. Si pide permiso, activa
   "Instalar apps de origen desconocido" para el navegador o administrador de archivos.

Para cambiar el juego, edita www/index.html y vuelve a subirlo: se genera un APK nuevo.
Nota: es un APK de depuración, suficiente para instalar y probar. Para publicar
en Google Play se necesita un APK/AAB firmado con tu propia llave.
