GastosRealApp_Full - Proyecto listo para abrir en Android Studio.

Características incluidas:
- Categorías y subcategorías detalladas embebidas.
- Guardar gastos con categoría + subcategoría + notas + viaje/regalo.
- Exportar a CSV (compatible con Excel).
- Importar desde CSV.
- Backup (exportar JSON) y Restaurar (importar JSON).
- FileProvider configurado para compartir archivos.

Pasos para generar el APK:
1) Descarga y descomprime este proyecto.
2) Abre Android Studio -> Open -> selecciona la carpeta del proyecto.
3) Sincroniza Gradle (puede pedir instalar dependencias).
4) Conecta un dispositivo o ejecuta un emulador.
5) Build > Build Bundle(s) / APK(s) > Build APK(s).
6) APK en app/build/outputs/apk/debug/app-debug.apk

Notas importantes:
- No puedo compilar el APK en este entorno; debes generar el APK en tu PC con Android Studio.
- Para backups automáticos en Google Drive necesitas integrar Google Drive API + OAuth (puedo guiarte).
- Si quieres, te hago un paso a paso con capturas para firmar el APK y publicarlo en Google Play.
