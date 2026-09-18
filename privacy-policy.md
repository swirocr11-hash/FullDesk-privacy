# Política de privacidad de OverlayVideoPlayer

**Última actualización:** [FECHA]

Esta política de privacidad describe cómo OverlayVideoPlayer ("la aplicación") maneja la información al usarse en tu dispositivo.

## 1. Quién publica esta aplicación

- **Desarrollador/publicador:** [TU NOMBRE O RAZÓN SOCIAL]
- **Contacto:** [TU CORREO DE CONTACTO]

## 2. Qué información recopila la aplicación

OverlayVideoPlayer **no recopila, almacena ni transmite información personal** a su desarrollador ni a terceros. La aplicación no requiere cuentas de usuario, no incluye telemetría ni analítica, y no envía datos a ningún servidor propio.

Las únicas preferencias que la aplicación guarda son configuraciones locales del propio dispositivo, y nunca salen de él:

- Posición y tamaño de cada ventana overlay.
- Rutas de los archivos de video/GIF que registraste en el Gestor de videos.
- Estado de silencio y nivel de volumen de cada ventana.
- Idioma detectado del sistema.

Estos datos se guardan usando el almacenamiento de configuración estándar de Windows (registro del sistema, a través de `QSettings`) y son accesibles y eliminables por ti en cualquier momento desinstalando la aplicación o borrando su configuración.

## 3. Conexión a internet

La aplicación funciona sin conexión a internet para su uso principal (reproducir un video o GIF de forma flotante en el escritorio).

La única excepción es la función opcional de **eliminación de fondo por IA**: la primera vez que se usa esta función, la aplicación descarga automáticamente un modelo de inteligencia artificial de código abierto (a través de la librería `rembg`) desde el repositorio público del proyecto. Esta descarga:

- No incluye ni transmite ningún dato personal ni identificador del usuario.
- Ocurre una sola vez; el modelo queda almacenado localmente en tu equipo y no se vuelve a descargar en usos posteriores, salvo que borres manualmente esos archivos.

## 4. Servicios de terceros

La aplicación utiliza las siguientes librerías de código abierto para su funcionamiento, ninguna de las cuales recopila datos personales del usuario en el contexto de esta app:

- PySide6 (Qt) — interfaz gráfica y reproducción de audio/video.
- OpenCV — procesamiento de video.
- rembg / onnxruntime — eliminación de fondo (opcional, bajo demanda del usuario).
- keyboard — atajos de teclado globales dentro de la propia aplicación.

## 5. Menores de edad

OverlayVideoPlayer no está dirigida a menores de 13 años ni recopila intencionalmente información de menores.

## 6. Cambios a esta política

Esta política puede actualizarse si la aplicación incorpora nuevas funciones que impliquen el manejo de información. Cualquier cambio se reflejará en esta misma página, actualizando la fecha indicada arriba.

## 7. Contacto

Si tienes preguntas sobre esta política, puedes escribir a: [TU CORREO DE CONTACTO]
