# **Advanced Irrigation System**

**Problem Statement:**

To create an advanced automated irrigation system which can keep track the current atmospheric and weather conditions like moisture in soil and humidity present and accordingly turn on/off the water supply with updating the status of water pump and soil moisture by sending and recieving message.

**Ideation

- Understanding the mechanism: 

`Temp.,Humidity and Soil Moisture sensor`=>Input for `Microcontroller`(Analyse the input signal)=>give command to `Relay`=>`Water Pump` 
=>`Irrigation to plants.`

dispaly the data recieved from differnt sensors <=`Microcontroller`=>Send Updates and Recieve messages

Here we have used
- Arduino UNO as microcontroller
  SIM800L for sending and recieving messages
  DHT11 sensor for temperature and humidity 
  soil moisture sensor
  LCD to display the data recieved from sensors
  
| Component | Replaceable by | Advantage | Disadvantage |
| --- | --- |
| Arduino UNO | TTGO T-Call | This is an ESP32 devlopment board which comes with integrated SIM800L GSM GPRS module and wireless(wifi and bluetooth) connectvity. We can also send data to third party server like ThingSpeak and it is much faster than Arduino | it is slightly on the expensive side in comparison to arduino |







