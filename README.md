nosara-sunrise-alarm-clock
==========================

-- Nosara Sunrise Alarm Clock --

This code is for a sunrise alarm clock that runs off an Arduino Uno prototyping board.

Materials required include:
- Arduino Uno R3 prototype board
- A Digital LED strip, which is mounted above your bed. I taped mine to a yardstick and nailed the yardstick up.
- An Alarm On/Off switch. Any slide-switch will do.
- DS3234 RTC (Real Time Clock) breakout board, which keeps time for the Arduino. User can get this from Adafruit.com or Sparkfun.com


Later iterations (determined by public interest in the code or if I feel like it) will include:
- A buzzer that goes off after the sunrise is complete, in case you sleep through the light
- An MP3 device that plays nature sounds as the device gets brighter
- An interface that can display the time and change the alarm time without need of a PC/Mac



--- Assembly Instructions ---
The DS3234 RTC is plugged directly into the Arduino board and powered by holding the power pin HIGH and the ground pin LOW.
This is okay for the power usage of this device.
