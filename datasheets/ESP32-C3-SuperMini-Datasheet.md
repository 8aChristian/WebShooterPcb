# ESP32-C3 SuperMini Microcontroller Module

## 📌 Resumen General
El **ESP32-C3 SuperMini** es una placa de desarrollo compacta basada en el chip **Espressif ESP32-C3FN4** con arquitectura RISC-V de 32 bits y un solo núcleo.

## ⚙️ Especificaciones Principales
- **Procesador**: RISC-V 32-bit single-core @ hasta 160 MHz.
- **Memoria**: 400 KB SRAM, 384 KB ROM, 4 MB Flash integrada.
- **Conectividad**: Wi-Fi 802.11 b/g/n (2.4 GHz) + Bluetooth 5 (LE).
- **Voltaje de Operación (Lógico)**: 3.3V DC.
- **Voltaje de Entrada (Pin 5V/VCC)**: 3.3V a 6.0V.
- **Consumo en Deep Sleep**: ~5 µA.

## 🔌 Pinout y Mapeo en WebShooter
| Pin Físico | Pin ESP32 | Función en WebShooter | Descripción |
| :--- | :--- | :--- | :--- |
| **J1 Pin 1** | 3.3V | Entrada de Alimentación | Riel regulado 3.3V desde AMS1117 |
| **J1 Pin 2** | GND | Tierra del Sistema | Conexión al plano de masa común |
| **J1 Pin 3** | GPIO0 (ADC1_CH0) | Entrada Analógica FSR | Lectura de fuerza con divisor resistivo |
| **J2 Pin 1** | GPIO6 | Salida PWM ESC | Señal de control para motor BLDC (50-400Hz) |
| **J2 Pin 2** | GPIO7 | Disparo Solenoide | Compuerta lógica del MOSFET AO3400A |
| **J2 Pin 3** | GPIO8 | LED de Estado | Indicador LED en placa con R limitadora |
