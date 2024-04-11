# oXs RP2040 Transmitter (version Full telmetry)

This version accept all sensors supported by oXs RP2040.  
For un minimum Locator Transmitter version see [here](https://github.com/pierrotm777/oXs_Locator/tree/main/oXs_RP2040_Emitter/Emitter_Minimum).  

## Schematic
![Schematic](https://github.com/pierrotm777/oXs_Locator/blob/main/oXs_RP2040_Emitter/Emitter_And_Full_Telemetry/OXS_RP2040_Full_v1.2.png)  

## Print Circuit Board
  <table border="2">
  <tr>
  <td><img src="https://github.com/pierrotm777/oXs_Locator/blob/main/oXs_RP2040_Emitter/Emitter_And_Full_Telemetry/OXS_RP2040_Full_Top.jpg" border="0"/></td>
  <td><img src="https://github.com/pierrotm777/oXs_Locator/blob/main/oXs_RP2040_Emitter/Emitter_And_Full_Telemetry/OXS_RP2040_Full_Bot.jpg" border="0"/></td>
  </tr>
  </table>

## Upload Firmware
You will find the original firmware [here](https://github.com/mstrens/oXs_on_RP2040/tree/test)  
  * Compile with with VSCODE
```
To do
```
  * Upload to RP2040  
    * Unzip zip file on your PC  
	![src](https://github.com/pierrotm777/oXs_Locator/blob/main/oXs_EPS8266_Receiver/source_code.png)  
    * Keep only the **src** folder  
    * Rename **scr** name by **oXs_locator_receiver**  
	* Rename the **oXs_locator_receiver.cpp** by **oXs_locator_receiver_on_esp8266.ino**  
	* Copy the oXs_locator_receiver folder to your Arduino Sketchbook Location  
	* Open your Arduino IDE  
	* Follow the instructions on this [web page](https://github.com/sparkfun/Arduino_Boards) for install ESP8266 boards  
	* Select LOLIN(WEMOS) D1 R2 & mini board  
	![src](https://github.com/pierrotm777/oXs_Locator/blob/main/oXs_EPS8266_Receiver/Wemos_D1_mini.png) 
	* Select your COM port  
	* Upload to your board  
	
	
