# bedtimeLEDs

Gently-changing rainbow LED lights that cycle continuously until you switch them off (or until 2 hours have passed and they auto-switch-off). Switch them on and off with just a Jedi hand-wave.

Hardware used:

* 1 x strip of generic WS2812B LEDs (NeoPixels), 30 per metre.
* 1 x Arduino Duemilanove
* 1 x infrared proximity sensor (https://www.sparkfun.com/products/242)

1. Connect the Arduino to the LED strip (instructions tbc).
2. Connect a distance sensor (instructions tbc).
3. git clone this repository into your home directory
4. Upload the `sketchbook/bedroom_lights/bedroom_lights.ino` sketch to the Arduino.
