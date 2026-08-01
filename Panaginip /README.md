Arduino Uno

diagram.json

#include <LiquidCrystal_I2C.h>

LiquidCrystal_I2C LCD(0x27, 16, 2);

void setup() {
  LCD.init();
  LCD.backlight();

  LCD.setCursor(0, 0);
  LCD.print("Hello Wokwi!");

  LCD.setCursor(0, 1);
  LCD.print("Arduino Uno");
}

void loop() {

}

Library Manager LiquidCrystal I2C

Wiring 
GND / GND 
VCC / 5V 
SDA / A4 
SCL / A5
