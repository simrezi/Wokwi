Arduino Uno

diagram.json

{
  "version": 1,
  "author": "Anonymous maker",
  "editor": "wokwi",
  "parts": [
    { "type": "wokwi-arduino-uno", "id": "uno", "top": 0, "left": 0, "attrs": {} },
    {
      "type": "wokwi-lcd1602",
      "id": "lcd1",
      "top": -3.2,
      "left": -42.4,
      "attrs": { "pins": "i2c" }
    }
  ],
  "connections": [
    [ "lcd1:GND", "uno:GND.1", "black", [ "h-9.6", "v-38.4", "h163.2" ] ],
    [ "lcd1:VCC", "uno:5V", "red", [ "h-9.6", "v105.7", "h48", "v67.2", "h163.2" ] ],
    [ "lcd1:SDA", "uno:A4", "green", [ "h-19.2", "v105.8", "h48", "v67.2", "h259.2" ] ],
    [ "lcd1:SCL", "uno:A5", "green", [ "h-9.6", "v173.1", "h307.2" ] ]
  ],
  "dependencies": {}
}

Library Manager
LiquidCrystal I2C

Wiring
GND / GND
VCC / 5V
SDA / A4
SCL / A5
