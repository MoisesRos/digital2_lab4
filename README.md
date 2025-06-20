# Laboratorio 4 - Comunicación I2C entre Microcontroladores

![Protocolo](https://img.shields.io/badge/Protocolo-I2C-blue) 
![Microcontrolador](https://img.shields.io/badge/Microcontrolador-ATmega328P-green) 
![Dispositivos](https://img.shields.io/badge/Dispositivos-3_Nodos-orange) 
![UVG](https://img.shields.io/badge/Universidad-UVG-red)

## Resumen General
Implementación de un sistema multi-microcontrolador con comunicación I2C que incluye:
- **Maestro**: Coordina la comunicación y muestra datos en LCD
- **Esclavo 1**: Contador de 4 bits con visualización en LEDs
- **Esclavo 2**: Lectura de potenciómetro mediante ADC
- **Librería personalizada** para manejo del bus I2C

## Características Principales

### 1. Arquitectura I2C
- **Topología maestro-esclavo** con 3 nodos
- **Direccionamiento único** para cada esclavo
- **Velocidad estándar** (100kHz)
- **Detección de colisiones** y manejo de errores
