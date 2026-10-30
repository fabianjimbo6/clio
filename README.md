# Clean Launcher — Edición Renault Clio II (Fabian) para Radio F9211B

![Vista previa del Launcher Renault Clio II](docs/screenshot.png)

Versión personalizada de **Clean Launcher** adaptada específicamente para **Fabian**, su **Renault Clio 2 Rojo** y su radio retráctil **Android F9211B (XYAuto / MediaTek AC8227L)**.

## Cambios realizados en esta versión

1. **Tarjeta Izquierda ("Hola, Fabian" + Renault Clio 2 Rojo + Botón Waze):**
   - Saludo personalizado con tu nombre (`Hola, Fabian`) y subtítulo `Renault Clio II`.
   - Imagen integrada de tu **Renault Clio 2 Rojo** con versión de luces apagadas (`optra.png`) y **luces encendidas (`optra_lights.png`)** que se iluminan automáticamente en modo nocturno o al tocar el auto.
   - Si en cualquier momento quieres poner una foto real tomada a tu propio carro, mantén presionado el auto (o toca el icono pequeño de auto arriba a la derecha) y elige **"Elegir foto"**.
   - Se reemplazó el cuadro del clima por un **acceso directo grande a WAZE** (`Iniciar navegación GPS`).
2. **Tarjeta Central Superior (Reloj y Fecha Limpios):**
   - Reloj grande y fecha en español, eliminando el aviso de cambio de aceite para que la interfaz quede limpia.
3. **Tarjeta Central Inferior (Radio FM compatible con F9211B):**
   - Compatible tanto con los paquetes de Radio FM de placas **XYAuto F9211B** (`com.autochips.fmradio`, `com.xyauto.fmradio`, `com.android.fmradio`) como con radios NWD.
4. **Tarjeta Derecha (Música / Spotify / Bluetooth):**
   - Muestra la carátula y canción actual de Spotify, YouTube Music, reproductor USB o Bluetooth, con controles grandes de Play/Pausa y Siguiente/Anterior.
5. **Barra Inferior (Los 7 botones originales):**
   - Navegación (abre **Waze** directamente), Bluetooth, Radio FM, Anillo central (Cajón de aplicaciones + selector de Tema Claro/Oscuro/Automático), Apagar pantalla (para manejar de noche sin reflejos), Ecualizador y Ajustes.
6. **Eliminación de audios ajenos:**
   - Se eliminaron los 48 audios `.mp3` del dueño anterior (*"Hola papacito"*, Pico y Placa de Quito, etc.).

## Cómo obtener el archivo `CleanLauncher.apk` sin instalar nada pesado en tu PC

El proyecto incluye compilación automática en la nube mediante GitHub Actions (`.github/workflows/build.yml`):
1. Crea un repositorio en [GitHub](https://github.com) y sube el contenido de la carpeta `CleanLauncher-Clio2`.
2. Entra a la pestaña **Actions** de tu repositorio: verás que GitHub compila automáticamente el proyecto en 1 minuto y te deja descargar el archivo **`CleanLauncher.apk`** listo para instalar.
3. Si prefieres compilarlo en tu PC con Windows, ejecuta `sh build.sh` teniendo Android SDK (`android-33`) y JDK 17.
