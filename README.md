📡 NTC Thermistor Temperature Sensor
📌 Overview

This project implements a temperature sensing system using an NTC thermistor and op-amp based signal conditioning.

The circuit converts temperature variation into a measurable voltage output.

⚙️ Specifications
Supply Voltage: 5V
Temperature Range: 30°C to 60°C
Output Voltage Range: ~0.4V to 4.4V
Thermistor Type: NTC
Op-Amp: MCP6004 (simulated using LTSpice model)
🔧 Circuit Description

The system consists of two stages:

1. Thermistor Voltage Divider
Converts resistance variation into voltage
2. Signal Conditioning Stage
Inverts and amplifies signal
Produces increasing output with temperature
📊 Simulation Results

The output voltage increases approximately linearly with temperature:

Temperature	Output Voltage
30°C	~0.4V
60°C	~4.4V
📷 Results
Circuit Diagram

Output Graph

⚠️ Note

Hardware implementation was not performed due to unavailability of components. The design is validated through LTSpice simulation.

🚀 Future Improvements
Hardware implementation using MCP6004
Calibration for precise output range
Noise filtering (50Hz suppression)
Data logging integration
🧠 Skills Demonstrated
Analog circuit design
Signal conditioning
LTSpice simulation
Sensor interfacing