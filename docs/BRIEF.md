# study-buddy-copperhead

An ESP32-C3 mini MCU based desk top study buddy device having following interfaces and functions:
Interfaces
- Ultrasonic sensor over a generic digital interface
- OLED Display over I2C
- Temperature and Humidity sensor, DHT22
- RGB LEDs for ambience
- 4 x User buttons 
- A single tone buzzer
- Powered by USB 2.0

Functions
- A pomodoro timer over the display configured by the user through buttons (start/stop/up/down)
- Ultrasonic sensor does the user presence monitoring at the desk. If away, pauses the timer and beeps
- Temperature and humidity shown over the display, RGB lights controlled according to it
- Connects over WiFi to a mobile app for statistics logging and alerts if any 

Define the architecture based on this requirement and build PCB ready for fabrication, as compact as possible - preferably palm size. Plan the placement of components according to the application requirement.
