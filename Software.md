<Information about software used in Raspberry Pi and ESP board, issues, screens> 

## Software used in my project:
- Domoticz: https://github.com/domoticz/domoticz
- Monit: https://github.com/arnaudsj/monit
- ESPEasy: https://github.com/letscontrolit/ESPEasy


Domoticz:
<img src="https://github.com/rureverek/Irrigation-controller-2020/blob/master/domoticz1.png"
     alt="Domoticz1"
     style="float: left; margin-right: 10px;" />
     Fig 1. Switch panel
     
Swtich panel provides information about the current state of switches allow to change this state manually, set automatic timer or program for changing any state.
     
 <img src="https://github.com/rureverek/Irrigation-controller-2020/blob/master/domoticz2.png"
     alt="Domoticz2"
     style="float: left; margin-right: 10px;" />
Fig 2. The setting page for switch.

Setting page contains important information for Domoticz Service for correct behaviour of switch e.g. Off/On Command Path, Idx of switch, Type and Delay.

 <img src="https://github.com/rureverek/Irrigation-controller-2020/blob/master/domoticz3.png"
     alt="Domoticz3"
     style="float: left; margin-right: 10px;" />
     
Fig 3. The program for irrigation system.

As shown on figure, Domoticz client page provides the tool for programming switch states depending on time/states etc using Blocky interface. Also there are much advanced options and Domoticz allows for creating programs in different languages like Python. Here is example of my irrigation lane program: switch is turned on for 30 mins at 4 am every day.
