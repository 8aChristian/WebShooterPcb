# Lista de Materiales (Bill of Materials - BOM) - WebShooter v1.0

| Item | Designador | Cant | Valor | Encapsulado | Descripción | Fabricante / Nro Parte | Código LCSC |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| 1 | `J1, J2` | 2 | **PinSocket_1x08_P2.54mm** | `Connector_PinSocket_2.54mm:PinSocket_1x08_P2.54mm_Vertical` | Zócalo hembra 1x8 2.54mm para ESP32-C3 SuperMini | Generic | `C224522` |
| 2 | `J_BATT` | 1 | **JST_XH_B2B-XH-A** | `Connector_JST:JST_XH_B2B-XH-A_1x02_P2.50mm_Vertical` | Conector Batería LiPo 2S (7.4V) | JST / B2B-XH-A | `C157929` |
| 3 | `J_SOL` | 1 | **JST_XH_B2B-XH-A** | `Connector_JST:JST_XH_B2B-XH-A_1x02_P2.50mm_Vertical` | Conector Válvula Solenoide (7.4V) | JST / B2B-XH-A | `C157929` |
| 4 | `J_FSR` | 1 | **JST_PH_B2B-PH-K** | `Connector_JST:JST_PH_B2B-PH-K_1x02_P2.00mm_Vertical` | Conector Sensor de Presión FSR402 | JST / B2B-PH-K | `C131337` |
| 5 | `J_ESC` | 1 | **PinHeader_1x03_P2.54mm** | `Connector_PinHeader_2.54mm:PinHeader_1x03_P2.54mm_Vertical` | Conector de señal PWM y GND para ESC | Generic | `C49257` |
| 6 | `U1` | 1 | **AMS1117-3.3** | `Package_TO_SOT_SMD:SOT-223-3_TabPin2` | Regulador LDO 3.3V 1A | Advanced Monolithic Systems / AMS1117-3.3 | `C6186` |
| 7 | `Q1` | 1 | **AO3400A** | `Package_TO_SOT_SMD:SOT-23` | MOSFET N-Channel 30V 5.7A Logic Level | Alpha & Omega Semi / AO3400A | `C20917` |
| 8 | `D1` | 1 | **SS14** | `Diode_SMD:D_SOD-123` | Diodo Schottky Flyback 40V 1A | MDD / SS14 | `C2480` |
| 9 | `D2` | 1 | **LED_0805_Blue** | `LED_SMD:LED_0805_2012Metric` | LED de Estado SMD 0805 | Everlight / 19-217/BHC-AP1Q2/3T | `C2290` |
| 10 | `C_IN` | 1 | **10uF 25V X7R** | `Capacitor_SMD:C_0805_2012Metric` | Condensador Cerámico SMD 0805 | Samsung / CL21B106KOQNNNE | `C15850` |
| 11 | `C_OUT` | 1 | **22uF 10V X7R** | `Capacitor_SMD:C_0805_2012Metric` | Condensador Cerámico SMD 0805 | Samsung / CL21B226MPQNNNE | `C45783` |
| 12 | `C_FILT` | 1 | **100nF 50V X7R** | `Capacitor_SMD:C_0805_2012Metric` | Condensador Filtro FSR SMD 0805 | Yageo / CC0805KRX7R9BB104 | `C49678` |
| 13 | `R_REF, R_PD` | 2 | **10k 1%** | `Resistor_SMD:R_0805_2012Metric` | Resistencias SMD 0805 (FSR ref & Gate PD) | Uniroyal / 0805W8F1002T5E | `C17414` |
| 14 | `R_PROT, R_LED` | 2 | **1k 1%** | `Resistor_SMD:R_0805_2012Metric` | Resistencias SMD 0805 (ADC prot & LED) | Uniroyal / 0805W8F1001T5E | `C17513` |
| 15 | `R_G, R_PWM` | 2 | **100 1%** | `Resistor_SMD:R_0805_2012Metric` | Resistencias SMD 0805 (Gate & PWM damp) | Uniroyal / 0805W8F1000T5E | `C17407` |
| 16 | `TP_VBATT..TP_GATE` | 6 | **TestPoint_Pad_D1.5mm** | `TestPoint:TestPoint_Pad_D1.5mm` | Puntos de prueba SMD para depuración | Keystone / Generic | `N/A` |
