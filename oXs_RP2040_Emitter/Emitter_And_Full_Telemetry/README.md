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
  * Compile with own firmware with VSCODE  
    Follow this [tutorial](https://github.com/mstrens/oXs_on_RP2040#----------software--------------------)  
	
  * Upload to RP2040  
    * Unzip zip file on your PC  
	![src](https://github.com/pierrotm777/oXs_Locator/blob/main/oXs_RP2040_Emitter/Emitter_And_Full_Telemetry/oXs_RP2040.png)  
	* Hold the BOOT button on your RP2040 and connect your USB cable  
	![src](https://github.com/pierrotm777/oXs_Locator/blob/main/oXs_RP2040_Emitter/Emitter_And_Full_Telemetry/RP2040_Upload.png)  
	Drag oXs.uf2 file into the opened folder  
	
## Configure your RP2040
You can now use a serial terminal (like putty , the one from arduino IDE, ...)   and set it up for 115200 baud 8N1.  

A **?** key return **HELP** functions.  
A **Return** key give you the **oXs configuration's** module.  

processing cmd

Version = 2.13.1  
    Function                GPIO  Change entering XXX=yyy (yyy=255 to disable)  
Primary channels input    =  255  (PRI     = 5, 9, 21, 25)  
Secondary channels input  =  255  (SEC     = 1, 13, 17, 29)  
<b>Telemetry . . . . . . . . =    8  (TLM     = 0, 1, 2, ..., 29)  
GPS Rx  . . . . . . . . . =   13  (GPS_RX  = 0, 1, 2, ..., 29)  
GPS Tx  . . . . . . . . . =   12  (GPS_TX  = 0, 1, 2, ..., 29)</b>  
Sbus OUT  . . . . . . . . =  255  (SBUS_OUT= 0, 1, 2, ..., 29)  
RPM   . . . . . . . . . . =  255  (RPM     = 0, 1, 2, ..., 29)  
SDA (I2C sensors)   . . . . =  255  (SDA     = 2, 6, 10, 14, 18, 22, 26)  
SCL (I2C sensors)   . . . . =  255  (SCL     = 3, 7, 11, 15, 19, 23, 27)  
PWM Channels 1, 2, 3 ,4   =  255  255  255  255 (C1 / C16= 0, 1, 2, ..., 15)  
PWM Channels 5, 6, 7 ,8   =  255  255  255  255  
PWM Channels 9,10,11,12   =  255  255  255  255  
PWM Channels 13,14,15,16  =  255  255  255  255  
Voltage 1, 2, 3, 4        =  255  255  255  255 (V1 / V4 = 26, 27, 28, 29)  
RGB led . . . . . . . . . =   16  (RGB    = 0, 1, 2, ..., 29)  
Logger  . . . . . . . . . =  255  (LOG    = 0, 1, 2, ..., 29)  
ESC . . . . . . . . . . . =  255  (ESC_PIN= 0, 1, 2, ..., 29)  
<b>Locator CS  . . . . . . . =   29  (SPI_CS = 0, 1, 2, ..., 29)  
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;SCK . . . . . . . =   14  (SPI_SCK= 10, 14, 26)  
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;MOSI  . . . . . . =   15  (SPI_MOSI=11, 15, 27)  
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;MISO  . . . . . . =   28  (SPI_MISO=8, 12, 24, 28)</b>  
Output level High . . . . =  255  (HIGH = 0, 1, 2, ..., 29)  
Output level Low  . . . . =  255  (LOW  = 0, 1, 2, ..., 29)  

Esc type is not defined

**Protocol is Sport (Frsky)**  
CRSF baudrate   = 420000  
Logger baudrate = 115200  
PWM is generated at = 50 Hz  
Voltage parameters:  
&nbsp; &nbsp; &nbsp; &nbsp;Scales : 4.290000 , 50.000000 , 1.000000 , 1.000000  
&nbsp; &nbsp; &nbsp; &nbsp;Offsets: 0.000000 , 82500.000000 , 0.000000 , 0.000000  
&nbsp; &nbsp; &nbsp; &nbsp;No temperature sensors are connected on V3 and V4  
RPM multiplier = 1.000000  
Baro sensor is not detected  
Airspeed sensor is not detected  
&nbsp; &nbsp; &nbsp; &nbsp;No Vspeed compensation channel defined; oXs uses default settings  
First analog to digital sensor is not detected  
Second analog to digital sensor is not detected  
Foreseen GPS type is Ublox (configured by oXs) :**GPS is detected but has not (yet) a fix**  
Led color is normal (not inverted)  
Failsafe type is HOLD  
Lora module for locator is detected  
Acc/Gyro is not detected  

Gyro is not configured  

No sequencers are defined  

Config parameters are OK  
Press ? + Enter to get help about the commands  


