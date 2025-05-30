🏠 Home Automation System Using Arduino UNO
This project presents a low-cost, Bluetooth-based home automation system using an Arduino UNO. The system enables users to control household appliances (like lights, fans, etc.) using an Android smartphone, making homes smarter, safer, and more accessible — especially for the elderly and physically challenged.

📌 Project Overview
🔌 Control appliances via Bluetooth using an Android phone

📲 User-friendly interface through a GUI app or Bluetooth terminal

🧠 Uses Arduino UNO for processing logic

⚡ Relays used for safe switching of high-voltage devices

💬 Serial communication for input command reading and response

🧰 Components Required
Component	Quantity
Arduino UNO R3	1
2-Channel Relay Module	1
Bluetooth Module HC-05	1
Load (e.g., Light Bulb)	As needed
Power Supply (5V & 9V)	1 each
Jumper Wires	As needed
Breadboard / Vero Board	1
Android Phone (Bluetooth)	1

🔧 System Architecture
The system works by:

Connecting the Arduino UNO to a relay module and Bluetooth module (HC-05).

The user sends commands (e.g., A, B, C...) via a mobile phone.

Arduino processes these commands to toggle appliances ON or OFF.

Feedback can be optionally printed via serial monitor.

