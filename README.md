# Artemisa

Asistente de voz para Android. Este repositorio distribuye sus versiones instalables.

## Instalación y actualizaciones

Las descargas se publicarán en [Releases](https://github.com/AxtandDiabolisis/artemisa-updates/releases). La primera publicación está pendiente.

En Artemisa 0.2.0 o posterior, abre **Ajustes**, pega esta dirección en **URL HTTPS de versiones**, guarda y pulsa **Buscar actualizaciones**:

```text
https://github.com/AxtandDiabolisis/artemisa-updates/releases/latest/download/latest.json
```

El enlace funcionará cuando exista una versión publicada con el archivo `latest.json` adjunto. Las actualizaciones requieren conexión y confirmación de instalación en Android.

## Funcionamiento sin conexión

Artemisa incluye reconocimiento local y puede abrir aplicaciones y ejecutar comandos compatibles sin conexión. La búsqueda de música en Spotify y otras funciones de red requieren internet. El reconocimiento de voz en línea es opcional.

## Publicación de nuevas versiones

Cada versión debe incluir el APK y `latest.json`, con un `versionCode` mayor, la URL del APK y su SHA-256. Debe conservarse la misma firma de Android para actualizar sin desinstalar.

**Nunca publiques la clave privada de firma, contraseñas, tokens ni credenciales de Spotify en este repositorio.**

Artemisa es un prototipo; su funcionamiento con micrófono, Bluetooth, Spotify y permisos debe comprobarse en el teléfono.
