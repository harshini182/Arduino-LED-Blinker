# Arduino-LED-Blinker
My first Arduino project using Wokwi

# Arduino LED Blinker

## Description
A simple Arduino project that blinks an LED every second.

## Components Used
- Arduino Uno
- LED
- 220Ω Resistor

## Code

```cpp
void setup() {
  pinMode(7, OUTPUT);
}

void loop() {
  digitalWrite(7, HIGH);
  delay(1000);
  digitalWrite(7, LOW);
  delay(1000);
}
