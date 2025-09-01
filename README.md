🌞 Dual Axis Solar Tracking System (IoT with Raspberry Pi)
This project is an IoT-based Dual Axis Solar Tracking System built using Raspberry Pi. The system automatically aligns a solar panel in the direction of maximum sunlight using LDR (Light Dependent Resistor) sensors, thereby maximizing power generation efficiency.
Additionally, the harvested solar energy is used for wireless charging of an LED through copper coil-based power transfer.

🚀 Project Idea
The idea behind this project is to make solar panels self-adjustable to always face the sun:
A solar panel is mounted on top.
4 LDR sensors are placed around the panel to detect sunlight intensity.
Depending on which LDR detects more light, the system rotates:
Horizontally (360°) using a DC Motor (60 RPM).
Vertically (180°) using a Servo Motor (MG996R).
The Motor Driver (L298N) controls the motors based on signals from the Raspberry Pi.
A USB power supply manages the circuit power.
A copper wire coil enables wireless charging of an LED, powered by the solar panel.
This setup makes the system more efficient in capturing solar energy throughout the day.

🛠️ Components Used
Raspberry Pi (main controller)
Breadboard & Jumper Wires (circuit prototyping)
Solar Panel
Servo Motor (MG996R)
DC Motor (60 RPM)
LDR (Light Dependent Resistors) x4
Motor Driver (L298N)
USB Power Supply
Copper Wire Coil (for wireless LED charging)
LED

⚙️ Working Principle
LDR Sensors detect sunlight intensity from 4 different directions.
The Raspberry Pi processes the sensor values.
The panel rotates:
Horizontally (base rotation) via DC motor (360°).
Vertically (neck tilt) via servo motor (180°).
The system ensures that the solar panel is always aligned toward maximum sunlight.
The energy generated is also used to wirelessly light up an LED.

 Power from Solar → Copper Coil → Wireless LED Charging
🔋 Applications
Optimized solar energy harvesting.
Small-scale renewable energy projects.
Wireless charging demonstrations.
Educational IoT + embedded systems project.

🖥️ How to Run
Connect all hardware components as per the circuit diagram.
Install necessary libraries on Raspberry Pi:
Run the main script:
python3 kjjk.py

📌 Future Improvements
Add IoT dashboard for real-time solar tracking visualization.
Store performance data in the cloud for analysis.
Scale up for larger solar panel systems.

