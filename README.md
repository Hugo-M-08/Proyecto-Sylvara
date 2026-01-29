# Sylvara 🌿 | Sistema Inteligente de Gestión de Invernaderos

**Sylvara** es una plataforma de **Internet de las Cosas ** diseñada para modernizar la agricultura mediante el monitoreo y control automatizado de invernaderos. Este proyecto integra hardware embebido, servicios web y una interfaz móvil para optimizar el rendimiento de los cultivos y el uso eficiente de recursos hídricos.

## 🚀 Características Principales

- **Monitoreo en Tiempo Real:** Visualización de temperatura, humedad y niveles de luz mediante sensores conectados a un **ESP32**.
- **Control Remoto de Riego:** Activación manual y automática de sistemas de riego a través de la aplicación móvil.
- **Análisis de Datos Históricos:** Visualización de métricas filtradas por día, semana o mes para identificar patrones de crecimiento.
- **Gestión Multi-Invernadero:** Soporte para registrar y monitorear múltiples ubicaciones geográficas desde una sola cuenta.
- **Estadísticas de Cosecha:** Registro de éxitos y fallos en la producción para mejorar la toma de decisiones.

## 🛠️ Stack Tecnológico

### Hardware (Capa de Percepción)
- **Microcontrolador:** ESP32 (Programado en C++/Arduino).
- **Sensores:** Humedad de suelo, Temperatura (DHT11/22), LDR (Luz).
- **Comunicación:** Protocolo HTTP/JSON.

### Backend & Database (Capa de Servicio)
- **Lenguaje:** PHP (WebServices para la comunicación móvil-servidor).
- **Servidor:** Apache / MySQL.
- **Alternativa Escalable:** Arquitectura preparada para integración con **Firebase Realtime Database**.

### Frontend (Capa de Aplicación)
- **App Móvil:** Interfaz intuitiva enfocada en la experiencia de usuario (UX) para agricultores.
- **Gráficas:** Implementación de librerías para visualización de datos dinámicos.

## 📋 Estructura del Repositorio

- `/hardware`: Código fuente para el ESP32 (archivos .ino).
- `/backend`: Scripts en PHP y estructura de la base de datos SQL.
- `/app`: Código fuente del proyecto móvil.
- `/docs`: Diagramas de conexión y documentación técnica.

## 🔧 Instalación y Configuración

1. **Base de Datos:** Importa el archivo `sylvara_db.sql` en tu servidor MySQL.
2. **Backend:** Sube los archivos de la carpeta `/backend` a tu servidor Apache y configura las credenciales en `config.php`.
3. **Hardware:** Carga el código del ESP32 usando Arduino IDE, asegurándote de cambiar la URL del endpoint por la de tu servidor.
4. **Móvil:** Compila la aplicación y vincula la API de Sylvara.


### ✍️ Autor
**Ingeniero en TICs** - Hugo-M-08 🫂


**PD:** Si necesita el archivo de al app completo favor de contactar :))
