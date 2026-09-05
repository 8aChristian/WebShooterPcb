# SS14 Surface Mount Schottky Barrier Rectifier

## 📌 Resumen General
El **SS14** es un diodo rectificador Schottky de alta velocidad y baja caída de tensión directa, ideal para protección contra picos inductivos (*flyback/freewheeling*).

## ⚙️ Características Técnicas
- **Encapsulado**: SOD-123 / SMA.
- **Voltaje Inverso Repetitivo ($V_{RRM}$)**: 40V.
- **Corriente Media Directa ($I_{F(AV)}$)**: 1.0A.
- **Caída de Tensión Directa ($V_F$)**: $pprox 0.50	ext{V}$ a 1A.
- **Tiempo de Recuperación Inversa ($t_{rr}$)**: Ultrarrápido (< 10 ns).

## 🔌 Función en WebShooter
- Conectado en antiparalelo directo a través de los terminales de la válvula solenoide ($J_{SOL}$).
- Suprime la fuerza contraelectromotriz ($V = -L rac{di}{dt}$) al abrir el MOSFET $Q1$, protegiendo la unión de drenador y evitando perturbaciones electromagnéticas en el microcontrolador.
