# oXs Model Locator

oXs can be used to locate a lost model (if you add a LORA module).

The model is normally connected to the handset but when the model is on the ground, the range is quite limitted.  
So if a model is lost at more than a few hundreed meters, the handset will not get any telemetry data anymore.  
oXs allows to use a separate connection (with LORA modules) in order to have an extended range and have a chance to find back a lost model.  
This is possible because those modules use a lower frequency, a lower transmitting speed and a special protocol for long range.  
The LORA modules are SX1276/RFM95 that are sall and easily available (e.g. Aliexpress, ebay, amazon)  

## oXs mstrens github
  *  [Transmitter](https://github.com/mstrens/oXs_on_RP2040/tree/test)
  *  [Receiver](https://github.com/mstrens/oXs_locator_receiver_on_esp8266)
  
### How to do your own system
I created a transmission and reception boards set.  
  *  Transmitter  
     The transmitter uses a RP2040 associated with an RFM95W.  
     I have build two modules:  
     *  The first use a full telemetry system And the Lora system.  
	    You can find all files [First](https://github.com/pierrotm777/oXs_Locator/tree/main/oXs_RP2040_Emitter/Emitter_And_Full_Telemetry)  
     *  The second use a minimal board with only a RP2040 and the Lora system.  
	    You can find all files [Second](https://github.com/pierrotm777/oXs_Locator/tree/main/oXs_RP2040_Emitter/Emitter_Minimum)  
  *  Receiver  
     The receiver uses an ESP8266 associated with an RFM95W.   
	 You can find all files [Receiver](https://github.com/pierrotm777/oXs_Locator/tree/main/oXs_EPS8266_Receiver)  
	 
#### How to use the Locator system
	 A full documentation for how to use the system is [here](https://github.com/mstrens/oXs_locator_receiver_on_esp8266)
  


