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
- SIM800L for sending and recieving messages
- DHT11 sensor for temperature and humidity 
- soil moisture sensor
- LCD to display the data recieved from sensors

  
| Component | Replaceable by | Advantage | Disadvantage |
| --- | --- | --- | --- |
| Arduino UNO | TTGO T-Call | This is an ESP32 devlopment board which comes with integrated SIM800L GSM GPRS module and wireless(wifi and bluetooth) connectvity.  | it is slightly on the expensive side in comparison to arduino |
| Soil Moisture Sensor | Soil Moisture Sensor with Control Unit | It comes with control unit LM393 IC. With the help of this we can set differnt thresold for comparison and electronic decisions can be made | - |



The suggested approach for the project is quite good but some changes can make it more feasible and easy to use. 

**TTGO T-Call**:
This ESP32 based devlopment board is quite effective in comparison to Arduino.It has inbuilt GSM GPRS module(SIM800L) to send messages and make phone calls We can also send data to third party server like ThingSpeak (so that we can access the data anywhere)  and it is much faster than Arduino.

**Rain Sensosr**: 
Installing a Rain Sensor to the irrigation palnt will work as a power saver and water saver as well for the plant. We can connect it to the power supply through the Realy module(NO) which will cause the system to shut in the event of rainfall.









