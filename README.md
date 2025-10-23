# ESFV - Extract Subtitles From Video

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/J3J31N82KX)

![alt text](ESFV_1.0.0.png "1.0.0 version in Windows")

ESFV is a desktop application designed to extract text from videos using OCR (Optical Character Recognition).
It allows you to play videos, pause on specific frames, extract subtitles or any on-screen text,
edit them, and export them in .TXT or .SRT (standard subtitle) formats.

The application supports video formats MP4, MKV, AVI, and MOV.
It works with light/dark themes and supports Spanish and English interfaces.

                 -INSTALLATION AND EXECUTION-  

Download the executable file "ESFV.exe" from the link provided by the developer.
No installation required: simply run the “.exe” file by double-clicking it.
The window will open centered on the screen (minimum 1200x700 pixels).
If you use antivirus software, make sure it allows execution (false positives are common for .exe files).
Note: On the first run, EasyOCR will download language models (Spanish/English).
The executable is standalone and includes all necessary dependencies.

                      -USER INTERFACE-  

The interface is divided into two main panels:
Left Panel: Video Player.
Video area (black background with rounded corners).
Bottom controls: progress bar, navigation buttons, volume, and fullscreen.
Right Panel: OCR and Editing Module.
Theme and language selectors. Themes: Dark or Light. Languages: Spanish or English.
Recognition and cancel buttons.
Progress bar for OCR/export.
List of extracted text blocks (editable).
Export buttons.

                  -VIDEO PLAYER CONTROLS-  

📁 Open Video: Select a video file (MP4, MKV, AVI, MOV).
▶️ / ⏸️ Play/Pause: Starts or stops playback.
⏪ Rewind: Jumps back 2 seconds (once per click).
⏩ Fast Forward: Speeds up to 5x while pressed.
🔊 Volume: Toggle mute (M). Slider adjusts level (0–100%).
⛶ Fullscreen: Toggles fullscreen mode.
Progress Bar and Time
Drag to seek position.
Label shows current / total time (HH:MM:SS).
OCR Module: Text Extraction
Open a video.
Play and pause (Space) on the desired frame.
Click "🔍 Extract Text".
The app captures the current frame and processes it with OCR.
Result: If text is detected, a “Text Block” is created in the right panel list. A success message appears.
If no text is detected: Error message (“No text detected in the image”).
Cancel: “❌ Cancel Extraction” (confirmation dialog).
Block Editing:
Each block shows:
Number: Block #1, #2, etc.
Start: Capture time (HH:MM:SS, editable).
End: Initially empty; use “⏹️ Set End” to record the current position.
Validation: Format HH:MM:SS.
Delete: Removes the selected block.
Automatic scroll to the new block.

                        -TIPS-  

Pause on clear frames with visible text to improve OCR accuracy, and manually edit if needed.
The start time is set automatically,
but the end time must be set manually — let the video play forward and click “Set End”.

                    -EXPORT TEXT-  

Buttons are enabled when at least one block exists.

SRT
Verify Start - End time formats.
Errors: Dialog listing issues.

TXT
📄 Export TXT: Saves blocks as “[HH:MM:SS] Text here”.
Dialog: Choose output path (*.txt).

                  -KEYBOARD SHORTCUTS-  

Space: Play/Pause.
Left Arrow: Rewind 2s.
Right Arrow: Fast forward 5x (hold).
Up/Down Arrows: +10% / -10% volume.
M: Mute/Unmute.
F: Fullscreen.
F: Exit fullscreen.

------------------------------------------------------------------------------------------
------------------------------------------------------------------------------------------

ESFV es una aplicación de escritorio diseñada para extraer texto de videos
utilizando OCR (Reconocimiento Óptico de Caracteres).
Permite reproducir videos, pausar en frames específicos, extraer subtítulos o cualquier texto en el video,
editarlos y exportarlos en formatos .TXT o .SRT (subtítulos estándar).

La aplicación soporta videos en formatos MP4, MKV, AVI y MOV.
Funciona en temas claro/oscuro, interfaz en español/inglés.

                    -INSTALACIÓN Y EJECUCIÓN-

1. Descarga el archivo ejecutable "ESFV.exe" desde el enlace proporcionado por el desarrollador.
2. No requiere instalación: simplemente ejecuta el archivo ".exe" haciendo doble clic.
3. La ventana se abrirá centrada en pantalla (mínimo 1200x700 píxeles).
4. Si usas antivirus, asegúrate de que permita la ejecución (falsos positivos comunes en .exe).

Nota: En la primera ejecución, EasyOCR descargará modelos de idioma (español/inglés).
El ejecutable es standalone, incluye todas las dependencias necesarias.

                      -INTERFAZ DE USUARIO-

La interfaz se divide en dos paneles principales:

  - Panel Izquierdo: Reproductor de video.
  - Área de video (fondo negro con bordes redondeados).
  - Controles inferiores: Barra de progreso, botones de navegación, volumen y pantalla completa.
  - Panel Derecho: Módulo OCR y edición.
  - Selectores de tema e idioma. Temas: Oscuro o Claro. Idiomas: Español o Inglés. 
  - Botón de reconocimiento y cancelación.
  - Barra de progreso para OCR/exportación.
  - Lista de bloques de texto extraídos (editable).
  - Botones de exportación. 

               -CONTROLES DEL REPRODUCTOR DE VIDEO-

- 📁 Abrir Video: Selecciona un archivo de video (MP4, MKV, AVI, MOV).
- ▶️ / ⏸️ Reproducir/Pausar: Inicia o detiene la reproducción.
- ⏪ Retroceder: Salta 2 segundos hacia atrás (una vez por clic).
- ⏩ Avance Rápido: Acelera a 5x mientras se mantiene presionado.
- 🔊 Volumen: Alterna silencio (M). Deslizador ajusta nivel (0-100%).
- ⛶ Pantalla Completa: Alterna modo fullscreen.

Barra de Progreso y Tiempo
- Desliza para buscar posición.
- Etiqueta muestra tiempo actual / total (HH:MM:SS).

Módulo OCR: Extracción de Texto
   - Abre un video.
   - Reproduce y pausa (Espacio) en el frame deseado. 
   - Haz clic en "🔍 Extraer Texto".
   - La app captura el frame actual lo procesa con OCR.
   - Resultado: Si se detecta texto, se crea un "Bloque de Texto" en la lista derecha. Muestra mensaje de éxito.
   - Si no hay texto: Mensaje de error ("No se detectó texto en la imagen").
   - Cancelar: "❌ Cancelar Extracción" (confirma con diálogo).

Edición de Bloques:
   - Cada bloque muestra:
   - Número: Bloque #1, #2, etc.
   - Inicio: Tiempo de captura (HH:MM:SS, editable).
   - Fin: Vacío inicialmente; usa "⏹️ Establecer Fin" para usar posición actual.
   - Validación: Formato HH:MM:SS.
   - Eliminar: Elimina el bloque seleccionado.
   - Scroll automático al nuevo bloque.

                              -CONSEJOS-
1. Pausa en frames con textos claros para mejorar la precisión OCR y edita manualmente si hay errores.
2. El punto de inicio se configura automáticamente,
pero el final se establece manualmente, deja avanzar el video y haz clic en "establecer fin".


                          -EXPORTAR TEXTO-
Los botones se habilitan con al menos un bloque.

SRT
- Verifica formatos de tiempo de Inicio - Fin.
- Errores: Diálogo con lista.

TXT
- 📄 Exportar TXT: Guarda bloques como "[HH:MM:SS] Texto aquí".

Diálogo: Selecciona ruta (*.txt).

                       -ATAJOS DE TECLADO-

- Espacio: Reproducir/Pausar.
- Flecha Izquierda: Retroceder 2s.
- Flecha Derecha: Avance rápido 5x (mantén presionada).
- Flecha Arriba/Abajo: +10% / -10% volumen.
- M: Silenciar/Activar sonido.
- F: Pantalla completa.
- F: Salir de fullscreen.
