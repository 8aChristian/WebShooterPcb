# AO3400A N-Channel Enhancement Mode MOSFET

## 📌 Resumen General
El **AO3400A** de Alpha & Omega Semiconductor es un MOSFET de canal N de nivel lógico (*Logic-Level*) diseñado para conmutación de alta velocidad y baja resistencia en conducción.

## ⚙️ Características Técnicas
- **Encapsulado**: SOT-23 (3 pines).
- **Voltaje Drenador-Fuente ($V_{DS}$)**: 30V máx.
- **Voltaje Compuerta-Fuente ($V_{GS}$)**: $\pm 12	ext{V}$ máx.
- **Corriente Continua de Drenador ($I_D$)**: 5.7A a $25^\circ	ext{C}$.
- **Resistencia en Conducción ($R_{DS(on)}$)**:
  - $< 28	ext{ m}\Omega$ a $V_{GS} = 4.5	ext{V}$
  - $< 33	ext{ m}\Omega$ a $V_{GS} = 2.5	ext{V}$ (100% compatible con 3.3V lógico del ESP32).
- **Disipación de Potencia en WebShooter**:
  - Para solenoide a 7.4V con $I = 0.8	ext{A}$:
  - $P = I^2 	imes R_{DS(on)} = (0.8)^2 	imes 0.033 pprox 21.1	ext{ mW}$ (Elevación térmica $< 3^\circ	ext{C}$).

## 🔌 Conexión en Circuito
- **Pin 1 (Gate)**: Conectado a GPIO7 mediante $R_G = 100\,\Omega$ y pull-down $R_{PD} = 10	ext{ k}\Omega$.
- **Pin 2 (Source)**: Conectado al plano de masa común (GND).
- **Pin 3 (Drain)**: Conectado al terminal negativo de la válvula solenoide ($J_{SOL}$ Pin 2).
