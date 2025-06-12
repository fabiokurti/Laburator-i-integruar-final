🧪 STM32F1 Embedded Systems Assignments
This repository contains schematic-based embedded system projects using STM32 microcontrollers. Each student is assigned a unique sensor module to integrate with an STM32, applying their knowledge in sensor interfacing and system design.

📋 Project Overview
Microcontroller: STM32F103C8T6TR

Design Platforms: STM32CubeIDE, KiCad v6+

Communication Protocols: I2C, SPI, UART (depends on assigned sensor)

Each student is expected to complete the following steps:

🔧 Project Instructions
1. Schematic Review
Navigate to your assigned project folder.

Examine the included schematic diagram.

Use only the sensor shown in the schematic.

Interface the sensor with the STM32 using the correct communication protocol (I2C, SPI, UART, analog, or digital).

2. Library Setup
Each project folder includes the symbol and footprint for the sensor.

Ensure you import these into KiCad.

3. Schematic Design
Connect the sensor to the STM32 in STM32CubeMX.

Select the appropriate pins based on the protocol.

4. PCB Layout
Convert your schematic to a PCB layout.

Follow the correct board stackup depending on the project:

4-Layer Stackup:

Top: Signal

Layer 2: VCC

Layer 3: GND

Bottom: Signal

2-Layer Stackup:

Top: Signal

Bottom: GND

5. Design Rules
VCC traces: 0.3 mm

Signal traces: 0.15 mm

Via size: 0.6 mm (outer) / 0.3 mm (inner)

✅ Learning Objectives
Practice sensor interfacing with STM32 microcontrollers

Design and demonstrate a functional embedded system project