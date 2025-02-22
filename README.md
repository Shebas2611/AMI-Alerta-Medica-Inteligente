# AMI - Alerta Médica Inteligente


## Descripción

AMI es un sistema de detección de fatiga y emergencias médicas en conductores basado en ESP-32-CAM. Utiliza tecnologías de reconocimiento facial y ocular para detectar signos de fatiga, convulsiones o parálisis y emitir alertas para prevenir accidentes.


## 📌 Características
✅ Detección de fatiga y emergencias: Identifica signos de cansancio y crisis médicas en tiempo real.✅ Alertas inmediatas: Emite señales sonoras y puede contactar con emergencias.✅ Integración con ESP-32-CAM: Uso de reconocimiento facial y de ojos mediante OpenCV.✅ Eficiencia energética: Diseñado para operar con bajo consumo de energía en vehículos.


## 🚀 Tecnologías Utilizadas

🔹 Hardware: ESP-32-CAM, altavoces, sensores.🔹 Software: Python, OpenCV, Arduino IDE.🔹 Diseño: Impresión 3D para la carcasa del dispositivo.


## 🔧 Instalación

#### 1️⃣ Clonar el repositorio

git clone https://github.com/TU-USUARIO/AMI-AlertaMedicaInteligente.git
cd AMI-AlertaMedicaInteligente

#### 2️⃣ Instalar dependencias necesarias (Python y OpenCV)

Si el sistema usa procesamiento local, instala:

pip install opencv-python numpy

#### 3️⃣ Subir el código a la ESP-32-CAM

Descargar Arduino IDE: Arduino

Configurar Arduino IDE:

Archivo > Preferencias: Agregar URL:

https://dl.espressif.com/dl/package_esp32_index.json

Herramientas > Placa > Gestor de Tarjetas: Buscar e instalar ESP32.

Conectar ESP-32-CAM (usar adaptador USB a serial FTDI):

GND → GND, VCC → 5V, TX → RX, RX → TX, IO0 → GND (modo programación).

Seleccionar en Arduino IDE:

Placa: AI-Thinker ESP32-CAM

Puerto: Seleccionar el correcto.

Subir el código y presionar RESET si hay errores.

Obtener la IP desde el Monitor Serie y acceder desde el navegador.

