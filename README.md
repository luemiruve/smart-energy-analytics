# ⚡ Smart Energy Monitoring System (SEMS)
**Sistema Inteligente de Monitoreo Energético con IoT y Análisis de Consumo (NILM)**

---

## 📖 Descripción

El **Smart Energy Monitoring System (SEMS)** es una solución de ingeniería enfocada en la medición, análisis y optimización del consumo eléctrico en tiempo real.

El sistema integra hardware embebido (ESP32 + sensores eléctricos), comunicación IoT (MQTT), backend para almacenamiento y análisis, y un modelo de inteligencia artificial basado en NILM.

Permite identificar patrones de consumo energético, detectar desperdicios y sentar bases para sistemas de eficiencia energética en entornos residenciales e industriales.

---

## 🎯 Objetivo Técnico

Diseñar un sistema capaz de medir variables eléctricas desde un punto central, transmitir datos en tiempo real, analizar patrones de consumo y escalar hacia automatización energética inteligente.

---

## 🚀 Funcionalidades

- Medición de corriente y voltaje en tiempo real  
- Envío de datos vía MQTT  
- Almacenamiento en base de datos  
- Visualización de consumo energético  
- Detección de patrones eléctricos (base para NILM)  
- Arquitectura escalable para integración industrial  

---

## 🏗️ Arquitectura del Sistema

Sensores eléctricos
↓
ESP32 (Edge Computing)
↓
MQTT Broker
↓
Backend (API + procesamiento)
↓
Base de datos (PostgreSQL)
↓
Dashboard / Analytics

---

## 🛠️ Tecnologías Utilizadas

### Hardware
- ESP32  
- SCT-013 (Sensor de corriente)  
- ZMPT101B (Sensor de voltaje)  

### Software
- C++ (Arduino Framework)  
- Python (análisis de datos)  
- PostgreSQL  
- MQTT (protocolo IoT)  

---

## 🔌 Integración Hardware

| Componente | ESP32   | Descripción           |
|------------|---------|-----------------------|
| SCT-013    | GPIO 35 | Medición de corriente |
| ZMPT101B   | GPIO 34 | Medición de voltaje   |
| GND        | GND     | Referencia común      |

---

## 📁 Estructura del Proyecto

smart-energy-monitoring/
├── README.md
├── src/
├── backend/
├── database/
├── analytics/
├── docs/
└── architecture/

---

## ⚙️ Instalación

1. Clonar repositorio:

git clone https://github.com/luemiruve/smart-energy-analytics.git

2. Configurar credenciales en `config.h`

3. Compilar y subir código al ESP32

---

## 📊 Aplicaciones

- Monitoreo energético residencial  
- Optimización de consumo industrial  
- Base para sistemas de automatización (Industria 4.0)  
- Sistemas IoT para eficiencia energética  

---

## 🧠 Escalabilidad

- Integración con sistemas SCADA  
- Machine Learning (NILM avanzado)  
- Control automático de cargas  
- Integración con plataformas cloud (Azure IoT / AWS IoT)  

---

## 👨‍💻 Autor

**Luis Emilio Ruiz Vega**  
Ingeniería en Tecnologías de la Información y Comunicaciones  
Tecnológico Nacional de México  

---

## ⚠️ Estado del Proyecto

En desarrollo activo — enfocado en integración hardware + backend + analítica.
