# **GPS Tracker**

**Problem Statement**

To make a GPS tracking system which will show the real time position with the help of data obtained from differnt sattelites.

**Ideation**

- Understanding the mechanism
 Collecct data from satellites=>Decode the NMEA code=> upload it on online paltform
 
 ***NMEA is standard data format supported by all GPS manufacturers.***
 
 we have used
 - GPS module to collect data from satellite
 - Raspberry Pi to read the GPS module
 - show it on HTML web page
  
  
  | Component | Replacable by | Advanatge | Disadvantage
  | --- | --- | --- | --- |
  | Raspberry Pi | ESP32 | ESP32 is much cheaper than Raspberry Pi |  ESP32 has Low processing power and less memory in comparison to Raspberry Pi. |
  | GPS module | No need to replace | Low cost, Easy to use, Simple way of getting to your location and provide differnt type of data like no of satellite GPS connected to, lattitude, longitude, altitude | Inaccuracy of data and siganl or battery failure |
  
 Suggested Soution is quite good but a few replacemnt and addition more user friendly and cost effective. ESP32 can decode the NMEA code with a decent programming done on Arduino IDE and can interact with third party software like ThingSpeak so we can access the data anywhere(for example we can install in a car and can access the location of car online) and its 5X cheaper than Raspberry pi which reduces the cost of project significantly. And we can do onboard installation of OLED display connected to ESP32 which will show the cuurent location and we dont need to serch it for online we have this GPS tracker in our hand.
