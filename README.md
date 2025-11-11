# Arduino LED Blink QA Project

This project demonstrates a basic LED blinking program using Arduino. The LED connected to pin 13 turns ON and OFF with a fixed delay.  
The purpose of this project is to understand basic microcontroller GPIO control and document QA issues using GitHub.

---

## 🔧 Hardware Required
- Arduino Uno / Nano / Mega
- Built–in LED on Pin 13 (or External LED + 220Ω Resistor)
- USB Cable
- Arduino IDE (Software)

---

## 💻 Code Overview
The code uses:
- `pinMode()` to configure pin as output
- `digitalWrite()` to turn LED ON/OFF
- `delay()` to create blinking interval

```cpp
int ledPin = 13; // Built-in LED pin

void setup() {
  pinMode(ledPin, OUTPUT);
}

void loop() {
  digitalWrite(ledPin, HIGH);
  delay(1000);
  digitalWrite(ledPin, LOW);
  delay(1000);
}
Issue	What you did
Add Comments in Code	- Resolved 
Circuit Diagram Missing	- Open 
Blink Speed Flexibility	- Open 

