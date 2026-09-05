# Interlink Electronics FSR 402 Force Sensing Resistor

## 📌 Resumen General
El **FSR 402** es un sensor de resistencia variable por fuerza que disminuye su resistencia óhmica cuando se aplica presión mecánica sobre su área activa circular de 12.7 mm.

## ⚙️ Características Técnicas
- **Rango de Fuerza**: 0.2 N a 20 N (20 g a 2 kg).
- **Resistencia en Reposo (Sin Fuerza)**: $> 10	ext{ M}\Omega$.
- **Resistencia a Presión Moderada**: $pprox 10	ext{ k}\Omega$.
- **Resistencia a Presión Máxima**: $pprox 1	ext{ k}\Omega - 200\,\Omega$.

## 🔌 Circuito Divisor de Tensión y Filtrado
- **Topología**: $V_{ADC} = 3.3	ext{V} 	imes rac{R_{REF}}{R_{FSR} + R_{REF}}$ con $R_{REF} = 10	ext{ k}\Omega$.
- **Filtro Pasabajos**: $C_{FILT} = 100	ext{ nF}$ en paralelo con $R_{REF}$ ($f_c = rac{1}{2\pi R_{REF} C_{FILT}} pprox 159	ext{ Hz}$), eliminando rebotes y ruido de alta frecuencia.
- **Protección**: $R_{PROT} = 1	ext{ k}\Omega$ en serie antes del pin `GPIO0` del ESP32-C3 para limitar transitorios de corriente.
