# mqtt_esp8266_wemos_d1r1_to_Cloudmqtt.com
 
This code sends sample test string to cloudmqtt.com

The File Examples PubSub -> mqtt_esp8266 was used with small changes to Publish and subscribe from cloudmqtt.com another broker which uses a different port, and client.connect params.


The changes to code was in :
-- X ---
const char* ssid = "JioFiber-24";
const char* password = "welcome2ibm";
const char* mqtt_server = "m12.cloudmqtt.com";

---X--
void setup() {
  pinMode(BUILTIN_LED, OUTPUT);     // Initialize the BUILTIN_LED pin as an output
  Serial.begin(115200);
  setup_wifi();
  client.setServer(mqtt_server, 19757);
  client.setCallback(callback);
}

---X---
Look at line 92

![image](https://user-images.githubusercontent.com/14288989/174536178-78903100-fd84-4176-b7d4-4de0439a205a.png)



