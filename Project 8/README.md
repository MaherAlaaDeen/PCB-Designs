# 5V DC-DC Buck Converter Module
## Objective
The objective of this project is to design and construct a DC-DC buck converter to step down higher input voltages to a stable 5V DC output. This converter mimics the design of the Arduino's 5V buck converter to supply power to microcontrollers, sensors, and other low-voltage device

## Components Used
1. Electrolytic Capacitor (680µF, 25V): Provides input filtering to smooth out voltage ripples and stabilize the input supply.
2. LM2596S: A step-down (buck) voltage regulator IC that reduces the input voltage to 5V with high efficiency.
3. Schottky Diode (1N5824): Protects the circuit and provides a low forward voltage drop, improving efficiency.
4. Inductor (33µH): Smooths the current and reduces ripple at the output.
5. LED Indicator (with a 1kΩ Resistor): Indicates that the circuit is powered and the output is active.
6. Output Terminals (+VOUT and -VOUT): Deliver the regulated 5V DC output for external devices.
