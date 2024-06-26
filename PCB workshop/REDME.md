PCB WORKSHOP

Analog circuit

TOPIC – Touch Sensor Using BJT

INTRODUCTION –

Touch sensors are innovative devices that respond to changes in capacitance resulting from static charges generated by conductive objects. Their unique working principle enables them to detect touch interactions, making them ideal for various applications, including touch-sensitive buttons and interactive surfaces.

SIMULATION RESULTS –

Touch sensors work similarly to a switch. When they are subjected to touch, pressure, or force, they activate and act as a closed switch. When the pressure or contact is removed it acts as an open switch. A capacitive touch sensor contains two parallel conductors with an insulator between them. These conductors' plates act as capacitors with a capacitance value of C0.

When these conductor plates come in contact with our fingers, our finger acts as a conductive object. Due to this, there will be an uncertain increase in the capacitance. A capacitance measuring circuit continuously measures the capacitance C0 of the sensor. When this circuit detects a change in capacitance it generates a signal.

The resistive touch sensors calculate the pressure applied on the surface to sense the touch. These sensors contain two conductive films coated with indium tin oxide, which is a good conductor of electricity, separated by a very small distance. Across the surface of the films, a constant voltage is applied. When pressure is applied to the top film, it touches the bottom film. This generates a voltage drop which is detected by a controller circuit and the signal is generated thereby detecting the touch.

Components required –

| NAME | QUANTITY | COMPONENT |
| --- | --- | --- |
| T1  | 1   | NPN Transistor(BJT) |
| S1  | 1   | Pushbutton |
| R1  | 1   | 330Ω Resistor |
| D1  | 1   | Red LED |
| R2  | 1   | 1KΩ Resistor |
| BAT1 | 1   | 9V Battery |

EasyEDA simulation-

- Step-by-step design –

Open EasyEDA: Go to EasyEDA and log in.

- Create New Schematic:
- Click "Document" -> "New" -> "Schematic".
- Name the schematic.
- Place Components:
- NPN BJT Transistor: Search "NPN BJT" and place it.
- Resistors: Search "Resistor" and place two (R1 and R2).
- Pushbutton: Search "Pushbutton" and place it.
- VCC and GND: Place these symbols.
- Connect Components:
- R1: Connect one end to the Pushbutton and the other to the base of the transistor.
- Emitter to GND: Connect the emitter of the transistor to GND.
- R2: Connect one end to the collector and the other to VCC.
- Output from Collector: Connect the output node to the collector.
- Convert to PCB:
- Click "Design" - "Convert to PCB".
- Place the components on the PCB layout.
- Route Traces:
- Use the "Route" tool to connect all components.
- DRC Check:
- Click "Design" - "DRC Check".
- Fix any highlighted issues.
- Generate Gerber Files:
- Click "Fabrication Output" - "Gerber" to create the necessary files for manufacturing.

Digital circuit

Topic – 4-bit Full adder

INTRODUCTION –

A 4-bit full adder is a digital circuit that performs the arithmetic addition of two 4-bit binary numbers. This essential component in digital electronics is widely used in computing and digital signal-processing applications. The circuit calculates the sum of the input bits and handles the carry input and output, ensuring accurate arithmetic operations.

SIMULATION RESULTS –

The Four Bit Full Adder works interestingly. The XOR Gates are responsible for the addition of input bits. To get the full addition circuit we attach two AND gates with the circuit in such a way that the result of addition connects the OR Gate and we get the carry.

In the designing of the circuit, we simply make a small circuit of AND Gate and XOR Gate. Then we design a Circuit of **two bits Full Adder**. The cynosure of the circuit is, that we'll copy the block and arrange four blocks in a way that the output carry of the block becomes the input carry of the next. This cycle will continue and at the  fourth block we get the resultant carry of the whole calculation-

| NAME | QUANTITY | COMPONENT |
| --- | --- | --- |
| U4  | 1   | 4-Bit Adder |
| SW2, SW3 | 2   | DIP Switch SPST x 4 |
| D1, D2, D3 | 5   | Red LED |
| P1  | 1   | 5, 5 Power Supply |
| R1, R2, R3 | 5   | 1 kΩ Resistor |

Step-by-Step Design for a 4-Bit Full Adder in EasyEDA

- Open EasyEDA:
- Go to EasyEDA and log in.
- Create New Schematic:
- Click "Document" -"New" - "Schematic".
- Name the schematic appropriately
- Place Components:
- 4-Bit Adder :
  - Search for "4-bit adder" in the component library.
  - Place it on the schematic.
- DIP Switches (SW2, SW3):
  - Search for "DIP Switch SPST x 4" in the component library.
  - Place two of these on the schematic.
- Red LEDs (D1, D2, D3, D4, D5):
  - Search for "Red LED" in the component library.
  - Place five LEDs on the schematic.
- 1 kΩ Resistors (R1, R2, R3, R4, R5):
  - Search for "1 kΩ Resistor" in the component library.
  - Place five resistors on the schematic.
- Power Supply (P1):
  - Search for "Power Supply" in the component library.
  - Place the power supply on the schematic.
- Connect Components:
- Input Connections
- Output Connections
- Power and Ground
- Convert to PCB:
- Click "Design" - "Convert to PCB".
- Name the PCB layout and proceed.
- Place Components on PCB:
- Arrange the components on the PCB layout as per your design requirements.
- Route Traces:
- Use the "Route" tool to connect all components according to the schematic.
- DRC Check:
- Click "Design" - "DRC Check" to perform a Design Rule Check.
- Fix any highlighted issues to ensure the design is manufacturable.
- Generate Gerber Files:
- Click "Fabrication Output" - "Gerber" to create the necessary files for manufacturing the PCB.
