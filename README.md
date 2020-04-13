# Connect-NodeMCU-to-WiFi
This github includes the complete code to connect the NodeMCU ESP8266 Board to any WiFi Network

#include <ESP8266WiFi.h>      //Library
_______________________________________________________________________________

WiFi.begin("WiFiName", "WiFiPassword");     //Command to connect to a WiFi Network
_______________________________________________________________________________

WiFi.status();      //To check if it is connected to a Network or not.

Values: 

1) WL_CONNECTED	

2) WL_IDLE_STATUS

3) WL_CONNECT_FAILED		
	
