# Reconocedor de Comandos por Voz

Esta es una aplicación Android desarrollada en Kotlin que permite **reconocer comandos de voz personalizados** usando un modelo de aprendizaje automático entrenado con [Teachable Machine](https://teachablemachine.withgoogle.com/) e integrado mediante TensorFlow Lite. La app interpreta comandos hablados para controlar un **reproductor de música simple**.

## Funcionalidades

- Reconocimiento de comandos de voz en tiempo real
- Integración con modelo entrenado (.tflite)
- Reproductor de música controlado por voz
- Interfaz sencilla e intuitiva
- Sin necesidad de conexión a internet para funcionar

## Modelo de voz

El modelo fue creado con Teachable Machine y entrenado para reconocer comandos como:

- `Reproducir`
- `Siguiente`
- `Anterior`
- `Detener` (si aplica)

> El archivo del modelo `.tflite` se encuentra en la carpeta `assets/`.

## Tecnologías utilizadas

- **Kotlin**
- **Android Studio**
- **TensorFlow Lite**
- **Teachable Machine**
- **MediaPlayer API**

## Estructura del proyecto

```plaintext
ReconocedorComandos/
├── app/
│   ├── src/
│   │   └── main/
│   │       ├── java/... (código fuente)
│   │       ├── assets/ (modelo tflite)
│   │       └── res/ (interfaz gráfica)
├── build.gradle.kts
└── README.md
```

## Instrucciones para compilar

1. Clona este repositorio:
   ```bash
   git clone https://github.com/javisiierra/ReconocedorComandos.git
   ```
2. Abre el proyecto en Android Studio.
3. Asegúrate de tener configurado el SDK de Android.
4. Ejecuta la app en un emulador o dispositivo físico.

## Notas

- No subas el archivo `local.properties`.
- El APK generado no está incluido en el repositorio.
- Recuerda agregar permisos de audio en el `AndroidManifest.xml`.

