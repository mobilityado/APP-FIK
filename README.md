# Asegura tu Factor - Android

Aplicación Android WebView para:
https://mobilityado.github.io/FIK/

## Generar APK desde GitHub (sin Android Studio)
1. Crea un repositorio nuevo en GitHub.
2. Sube TODO el contenido de esta carpeta a la raíz del repositorio.
3. Abre la pestaña **Actions**.
4. Entra a **Generar APK Android**.
5. Ejecuta **Run workflow** (también se ejecuta automáticamente al subir cambios a `main`).
6. Al terminar, abre la ejecución y descarga el artefacto **AseguraTuFactor-APK**.
7. Dentro del ZIP estará `app-debug.apk`; ese archivo se instala en teléfonos Android.

## Compilar desde Android Studio
Abre esta carpeta como proyecto y usa:
Build > Build Bundle(s) / APK(s) > Build APK(s)

## Datos de la app
- Nombre: Asegura tu Factor
- Package: com.mobilityado.aseguratufactor
- URL inicial: https://mobilityado.github.io/FIK/
- Android mínimo: Android 7.0 (API 24)
- JavaScript/DOM Storage: habilitados
- Botón Atrás: navega dentro de la WebView
- Enlaces externos: abren en navegador
- Pantalla de error: incluida para falta de conexión
