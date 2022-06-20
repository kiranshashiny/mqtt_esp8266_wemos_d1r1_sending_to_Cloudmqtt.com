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
