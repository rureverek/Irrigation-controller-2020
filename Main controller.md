 <img src="https://github.com/rureverek/Irrigation-controller-2020/blob/master/schem.png"
     alt="Domoticz2"
     style="float: left; margin-right: 10px;" />
Fig 1. Schematic

Why I chose ESP8266 circuit for my controller project?
It has several major cons:
-	Small size
-	Built-in UART converter (CH340)! It’s extremely easy to program board using only USB cable
-	Allows both 3.3v and 5v power supply
-	Wide support available in network due to its popularity

During my project I had to face some problems with board such as:
-	Poor PCB antenna range
-	No external antenna socket (in my specific model, there are models with the socket for external antennas on the market)
-	The number of available GDPIO pins is greatly reduced since some of them have multiple functions such as I2C/PWM/Reset handling and using this board for more complex project can be inconvenient. However, it was enough for my project.

 <img src="https://github.com/rureverek/Irrigation-controller-2020/blob/master/img_controller1.JPG"
     alt="Domoticz2"
     style="float: left; margin-right: 10px;" />
Fig 2. Main controller box


I intent to place my controller circuit in basement while Local Network Router was placed on the first floor of building. I had to face problem with poor antenna. I erased the PCB antenna path and soldered the external antenna socket into it. In this way I managed to set my controller inside basement with quite good 60-70 dBm RSSI. 

 <img src="https://github.com/rureverek/Irrigation-controller-2020/blob/master/img_controller2.JPG"
     alt="Domoticz2"
     style="float: left; margin-right: 10px;" />
Fig 3. External antenna socket
