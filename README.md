# App Android Flet + SQLite

Este es un proyecto desarrollado con [Flet](https://flet.dev/) y una base de datos local **SQLite**, que permite gestionar un sistema de alquiler de herramientas para construccion de manera sencilla a través de una interfaz gráfica en Python.

## 📁 Estructura del proyecto

```
flet+sqlite/
├── assets/              # Carpeta de recursos (puede incluir imágenes, íconos, etc.)
├── alquiler.db          # Base de datos SQLite con la información de alquileres
├── main.py              # Archivo principal de la aplicación
└── requirements.txt     # Dependencias del proyecto
```

## 🚀 Requisitos

- Python 3.9 o superior
- pip (gestor de paquetes de Python)

## 🛠️ Instalación

1. Clona este repositorio o descarga los archivos

2. Instala las dependencias del proyecto:

```bash
pip install -r requirements.txt
```

3. Ejecuta la aplicación:

```bash
python main.py
```

## 📦 Empaquetar como APK

Para generar un archivo APK e instalar tu aplicación Flet en Android, sigue estos pasos:

### 🔧 Requisitos previos

Antes de ejecutar `flet build apk`, asegúrate de tener instalado:

- [Android Studio](https://developer.android.com/studio) (incluye Android SDK, NDK y emulador)
- [Flutter](https://docs.flutter.dev/get-started/install)
- Java Development Kit (JDK) 11 o superior
- Python 3.9 o superior
- pip

### ⚙️ Configuración inicial

1. Instala Flet CLI si no lo has hecho:

```bash
pip install flet
```

2. agrega al PATH (`sdkmanager`, `flutter`, etc.).

3. Ejecuta el siguiente comando en la raíz del proyecto:

```bash
flet build apk -v
```

Esto genera una carpeta `build/` y luego `dist/`, donde encontrarás el archivo `.apk` empaquetado para Android.




