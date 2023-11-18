# Smart-lighting-system
The process of creating an automated lighting control system for streetlights using motion detection. The system will turn ON/OFF the pole lights based on the movement of vehicles on the road.
Procedure:
Step 1: Take ESP32 Board.
Step 2: Connect PIR Sensors with the following mentioned connections:
PIR: (+) pin to ESP32: 5V pin.
PIR: (-) pin to ESP32: GND pin.
PIR: (D) pin to ESP32: D19 pin for PIR Sensor 1
PIR: (D) pin to ESP32: D21 pin for PIR Sensor 2
Step 3: Connect LED'S;s to ESP32 with following mentioned connections:
Connect the positive leg (Anode) of each LED to the output pins of the ESP32 in the following
Manner:
LED 1: (A) pin to ESP32: D32 pin.
LED 2: (A) pin to ESP32: D33 pin.
LED 3: (A) pin to ESP32: D25 pin.
LED 4: (A) pin to ESP32: D26 pin.
LED 5: (A) pin to ESP32: D27 pin.
Note: For LED positive and Negative Leg, please refer to the Component Description of the FAQ
Document.

Step 4: Connect LED to Resistor (1K ohm) with the following mentioned connections:
Connect the Negative leg (Cathode) of each LED to any leg of the resistor in the following
Manner:
LED 1: (C) pin to RES 1 pin.
LED 2: (C) pin to RES 2 pin.
LED 3: (C) pin to RES 3 pin.
LED 4: (C) pin to RES 4 pin.
LED 5: (C) pin to RES 5 pin.
Note: For LED positive and Negative Leg, please refer to the Component Description of FAQ
Document.
Note: Resistors can be used in any direction.

Step 5: Connect all Resistors (1K ohm) to another leg to the GND pin of ESP32.
Step 6: Burn the code to the ESP32 Board using Arduino IDE.
Step 7: Test the Project
The Leds should automatically turn on or off depending on the readings from the PIR sensor
on the basis of motion.
