# Voice Control Car

The robotic car can be controlled wirelessly via voice commands directly from the user. The robot can move forward, backward, left, and right and can also be stopped.

The Arduino voice-controlled robot car is interfaced with a Bluetooth module HC-05 or HC-06. We can give specific voice commands to the robot through an Android app installed on the phone. At the receiving side, a Bluetooth transceiver module receives the commands and forwards them to the Arduino and thus the robotic car is controlled.

![image](https://github.com/chitrakshkardam/Door-security-alarm/assets/117617336/76e055fc-4657-4d44-9bcc-4204f183cc8d)


Cicuit Diagram and Connections

![Uploading image.png…]()

The circuit consists of Arduino UNO Board, HC-05/HC-06 Bluetooth Module, L293D Motor Driver IC, a pair of DC Geared Motors of 200 RPM and a 9V Battery.

The TX, RX pins of Arduino is connected to Rx, Tx pins of Bluetooth Module. The Bluetooth Module is supplied with 5V. Similarly, left DC motor is connected to pin no 3 & 6 of L293D and right DC motor to pin no 14 & 11 of L293D. Arduino digital pins 2,3,4,5 is connected to L293D 2, 7, 10, 15 respectively.

The L293D IC Pins 2, 5, 12, 13 is GND pins, and 9, 1, 16 is supplied with 5V. But pin 8 of L293D is directly supplied with 9V.

