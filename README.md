# mqtt_esp8266_wemos_d1r1_to_Cloudmqtt.com
 
This code sends sample test string to cloudmqtt.com

The File Examples PubSub -> mqtt_esp8266 was used with small changes to Publish and subscribe from cloudmqtt.com another broker which uses a different port, and client.connect params.

---

The changes to code was in :

![image](https://user-images.githubusercontent.com/14288989/174536532-daebabb8-e656-41a1-ab5e-2f35dd6e310f.png)

---

Line 112

![image](https://user-images.githubusercontent.com/14288989/174536621-848f6864-4878-4e21-bb9b-167c6732e948.png)

---
Look at line 92

![image](https://user-images.githubusercontent.com/14288989/174536178-78903100-fd84-4176-b7d4-4de0439a205a.png)

---

The Broker CLOUDMQTT's Parameters are what is entered in the code.

![image](https://user-images.githubusercontent.com/14288989/174536854-d01febf7-dfaa-4ed3-ae2a-0c33578e5533.png)


---

The serial output from Arduino showing that the data is being sent.

![image](https://user-images.githubusercontent.com/14288989/174536975-14b5728b-da81-4dbf-b447-bb470c59b7c7.png)

---

Broker Cloudmqtt's interface showing that the data is being received from the Wemos D1 R1

![image](https://user-images.githubusercontent.com/14288989/174537151-e59b4563-7d40-4b86-9f62-0a4ce24234f1.png)


---
Compile parameters used for this Arduino sketch.

Look at Upload speed set to 115200,
and the port set to Wemos D1 R1 ( usbserial1420)

![image](https://user-images.githubusercontent.com/14288989/174537911-e91ab812-7c62-4873-af18-2027fd923c18.png)


---

Publish Message from cloudmqtt.com's interface seen on the Arduino Serial Monitor

![image](https://user-images.githubusercontent.com/14288989/174538382-2cf345aa-3084-418e-bff1-5c146d3a9d65.png)



---
Publish message being sent from the cloudmqtt.com's interface
![image](https://user-images.githubusercontent.com/14288989/174538501-29814628-b283-4471-a246-44a2d2a3affd.png)

---


The Pubsub client code API documentation

https://pubsubclient.knolleary.net/api

Look at connect's parameters

![image](https://user-images.githubusercontent.com/14288989/174538837-d1b30b1d-0fad-41f2-8e06-7d70bbac8784.png)



