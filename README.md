# 🎓 Carné ULima

![Flutter](https://img.shields.io/badge/Flutter-3.8-02569B?logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-3-0175C2?logo=dart&logoColor=white)
![Material 3](https://img.shields.io/badge/Material%203-757575?logo=materialdesign&logoColor=white)

> Carné universitario digital de la Universidad de Lima, hecho en Flutter.

App móvil que recrea el carné de estudiante de la **Universidad de Lima** en formato digital, con su **código de barras escaneable**, listo para mostrarse desde el celular.

<!-- Sugerencia: agrega una captura de la app aquí -->
<!-- ![Captura](assets/images/screenshot.png) -->

## Características

- **Carné digital** fiel al diseño del carnet físico (logo, foto y datos del alumno).
- **Código de barras** generado dinámicamente con `barcode_widget` — escaneable como el carnet real.
- **Animación suave** en la credencial usando `AnimationController`.
- **Diseño responsive** — la interfaz se adapta al tamaño de pantalla con `MediaQuery`.
- **Material 3** y tipografías personalizadas (Calibri, Inter).
- Ícono de app configurado para **Android e iOS**.

## Stack

| Capa | Tecnología |
|------|-----------|
| Framework | Flutter (SDK ^3.8) |
| Lenguaje | Dart |
| UI | Material 3 |
| Código de barras | `barcode_widget` |
| Íconos de app | `flutter_launcher_icons` |

## Cómo correrlo

**Requisitos:** tener [Flutter](https://docs.flutter.dev/get-started/install) instalado.

```bash
# 1. Clonar el repositorio
git clone https://github.com/skyluw/PassUL_Flutter.git
cd PassUL_Flutter

# 2. Instalar dependencias
flutter pub get

# 3. Ejecutar en un emulador o dispositivo conectado
flutter run
```

## Estructura

```
lib/
  main.dart         # App y pantalla del carné (CredencialPage)
assets/
  images/           # Logo de la ULima y foto
  icons/            # Ícono de la app
  fonts/            # Calibri, Inter
pubspec.yaml        # Dependencias y assets
```

## Autora

**Cielo Chávez** — [GitHub @skyluw](https://github.com/skyluw) · [LinkedIn](https://www.linkedin.com/in/cielo-chavez)
