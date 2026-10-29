# Arena Sombría · mini beta

Juego de peleas 2D original (1 vs CPU, mejor de 3 rondas, 3 luchadores + jefe).
Todo el juego vive en `app/src/main/assets/index.html`; la app Android es un WebView a pantalla completa.

## Cómo obtener el APK

**Opción A: sin instalar nada (GitHub Actions)**
1. Crea un repositorio nuevo en GitHub y sube el contenido de esta carpeta (incluida `.github`).
2. Entra en la pestaña *Actions* → *Build APK* → espera ~3 min.
3. Abre la ejecución y descarga `arena-sombria-apk` (dentro está `app-debug.apk`).
4. Pásalo al celular e instálalo (permite "instalar apps de orígenes desconocidos").

**Opción B: Android Studio**
Abre esta carpeta → *Build* → *Build APK(s)*. El archivo queda en `app/build/outputs/apk/debug/app-debug.apk`.

**Opción C: terminal** (con Android SDK instalado)
```
./gradlew assembleDebug
```

## Solo jugar (sin APK)
Abre `index.html` en Chrome del celular o de la PC. En PC se juega con teclado:
← → mover · ↑ saltar · J puño · K patada · L bloqueo · U especial (cuesta 50 de energía).
