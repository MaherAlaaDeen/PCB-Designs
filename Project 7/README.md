# High DC Voltage Sensor Module
## Objective
The objective of this project is to design and build a high-voltage sensor module capable of measuring DC voltages from 0 to 60 V. The module outputs a proportional voltage suitable for an Arduino's Analog-to-Digital Converter (ADC) input. It utilizes a voltage divider for scaling, a MOSFET for buffering and protection, and additional components for stability and signal conditioning.

## Components Used
1. Voltage Divider Resistors (R1 = 22kΩ, R2 = 2kΩ):
- - Scales the input voltage to a lower range compatible with the Arduino ADC (0–5 V).
2. MOSFET (IRF9Z24):
- - Functions as a buffer to isolate the voltage divider from the Arduino ADC input.
  - Provides additional protection and ensures accurate signal transmission.
3. Resistors (10kΩ, 100Ω):
- - Used with the MOSFET to set operating conditions and stabilize the circuit.
4. Ceramic Capacitor (0.1 µF):
- - Filters high-frequency noise from the voltage divider output.
5. Arduino ADC (Analog Input):
- - Reads the scaled and conditioned voltage and converts it into a digital value for processing.

## BOM

