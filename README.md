
 LED Blinking Using Arduino – Embedded System Project
📌 Overview
This project demonstrates a basic embedded system program to blink an LED using an Arduino Uno.  
It is created as part of an activity involving GitHub repository creation, QA issue logging, collaboration, and report submission.



 🔧 Hardware Requirements
- Arduino UNO
- USB Cable
- LED (optional if using pin 13 onboard LED)
- Jumper wires
---

🧾 Code Explanation
The program initializes pin 13 as an output and toggles the LED state every one second.

int ledPin = 13;

void setup() {
  pinMode(ledPin, OUTPUT);
}

void loop() {
  digitalWrite(ledPin, HIGH);
  delay(1000);
  digitalWrite(ledPin, LOW);
  delay(1000);
}
