# HOME AUTOMATION WITH BLUETOOTH

COMPANY : CODETECH IT SOLUTION

NAME : SHUBHAM DATTATRAY SURVE

INTERN ID : CT08DH2161

DOMAIN : EMBEDDED SYSTEM

DURATION : 8 WEEKS

MENTOR : NEELA SANTOSH KUMAR

The Home Automation using Serial Monitor and Arduino project demonstrates a basic yet powerful method of controlling electrical devices using a computer's serial terminal. Instead of using wireless communication modules like Bluetooth, this project uses the built-in Serial Monitor of the Arduino IDE to receive commands from the user. Based on the input commands like "ON" or "OFF" entered through the Serial Monitor, the Arduino processes the input and activates or deactivates connected appliances such as an LED (representing a light) or a motor (representing a fan).
The core of the project lies in the ability of the Arduino to read serial data, interpret string inputs, and trigger digital output pins accordingly. When the user types "ON" and presses enter, Arduino receives this string through the Serial.readString() function. It then compares the received string using if-else conditions. If the input matches "ON", the digital pin connected to the LED or device is set to HIGH, turning the device ON. Similarly, the "OFF" command turns the device OFF by setting the pin LOW.
This project is ideal for understanding serial communication, string handling in Arduino programming, and digital output control. Though basic, it lays the foundation for more complex automation systems such as Bluetooth, Wi-Fi, or IoT-based control, which also rely on receiving and processing user commands. It is a beginner-level project, best suited for students who want to practice controlling real-world devices through programming.

🔩 Components Used:

1. Arduino Uno – Central microcontroller
2. LEDs / Fan (DC Motor or relay-controlled) – Representing home devices
3. 220Ω Resistor – For LED protection
4. USB Cable – To connect Arduino to PC
5. Jumper Wires – For making connections
6. Breadboard – Circuit base platform
7. (Optional) Relay Module – If real AC appliances are to be connected

⚙️ Working Principle:

Arduino is connected to the PC via USB.
The Serial Monitor (from Arduino IDE) is used to send text commands like "ON" or "OFF".
Arduino reads these strings using Serial.readString() function.
It compares the received input:
If "ON" → the connected output pin is set HIGH → Light turns ON.
If "OFF" → the pin is set LOW → Light turns OFF.
Any additional devices can be controlled similarly by adding more conditions.

📍 Applications:

Low-cost home automation systems
Quick testing of automation logic
Lab simulations for relay-based switching
Educational use to teach serial communication
Foundation for Bluetooth/Wi-Fi automation expansion

🎯 Importance of Project:

Teaches serial communication using Serial Monitor
Develops understanding of string input and conditional logic
Enables control of real-world outputs from PC interface
Requires no extra wireless modules, cost-effective
Can be easily upgraded to Bluetooth/Wi-Fi based systems


✅ Output:

User opens Serial Monitor in Arduino IDE
Types "ON" → LED or Fan turns ON (connected pin goes HIGH)
Types "OFF" → Device turns OFF (pin goes LOW)

Output is visible instantly based on command

You can expand this with more devices and commands

