# Automatic garden hydration system using Raspberry PI

The aim of the project was to create automatic system to control water valves of garden hydration system. The system consists of several components:

### 1.	**Main valve controller** placed in basement. It consists from:
  -	**ESP8266 circuit** – the most important part in controller, allows for WiFi communication in 802.11 b/g/n standard. Thanks to UART interface and GPIO pins its perfect choice for simple remote control circuit. I booted the board with ESPEasy - compact software which provides utilities to integrate board with Domoticz service working on Raspberry Pi. 
  -	**Electromagnetic Switches Module** – allows for switching 18 AC Voltage for different valves
  -	**Compact 360AC – 5 V Power Supply** needed for Switches and ESP8266
  - **360AC – 18AC Transformer** which provide power for water valves
  -	**Prototype PCB** to simplify wire connections
  -	**Homemade plastic case** which I got from old box 😊
  -	**External antenna with prepared socket in box** instead of default PCB antenna
### 2. **Raspberry Pi** placed in living room near the local network router.
  - **Plastic case** for Raspberry printed in 3D printer. I use open-source project of case for that. Link(?)
  - Software:
    - Raspbian Lite
    - Domoticz service
    - Monit service
### 3. **The box with 5 electric water valves** placed in garden near water source.
  - Six water valves control six different pumplines of water irrigation system. System is designed to irrigate the surface of 800 squared meters in garden.
