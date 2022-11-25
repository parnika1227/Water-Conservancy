README

Abstract – 
Water is an essential resource in everyday life and its optimal management plays a major role. The important objective of this paper is to provide an automated and a Simplified system to govern water supply in multistorey buildings across distinct blocks for optimization of resources.

Introduction – 
Water makes up 70% of the earth as well as the human body. There are millions of marine species present in today’s world that reside in water. Similarly, humankind also depends on water. All the major industries require water in some form or the other. However, this precious resource is depleting day by day. The majority of the reasons behind it are man-made only. Thus, the need for water conservation is more than ever now. Water conservation and management encompasses the policies, strategies and activities made to manage water as a sustainable resource, to protect the water environment, and to meet current and future human demand. Population, household size, and growth and affluence all affect how much water is used. Factors such as climate change will increase pressures on natural water resources especially in industrial and agriculture.

SYSTEM ARCHITECTURE AND DESIGN – 
Unlike other systems, this System includes both Hardware and Software components. Initially we used Solenoid valves instead of the manual valves. We used electric signals to operate these valves. The prototype worked but it required a lot of wiring to connect valves and operate them from a single place.  At first, we tried to use Arduino but it was costly and it required an extra Wi-Fi module to be connected with the IoT cloud. After doing a lot of research we found the replacement for the Arduino. NodeMCU, it comes with built-in Wi-Fi module so there was no need for the extra component and the prototype worked without any errors. that we used Arduino uno and ESP8266 Wi-Fi module to connect these valves to a cloud and operate them from your app the idea was successful, and the prototype was working but now the problem that we were facing was that the Arduino was costly.




PROCEDURE
We replaced the manual valves with the solenoid valves. used a relay to transfer the E-signals from NodeMCU to the valve. Each building has a NodeMCU which has multiple valves connected to it that operate simultaneously. The NodeMCU on each building works as a slave that receives commands from a master NodeMCU that receives commands from the cloud, or the app used by the operator. On each of the buildings there will be a complete circuit for the NodeMCU and the Relay’s in it. It will use a less mount of wiring and save a lot of money as well.

Components Used –

SOLENOID VALVE
	Solenoid valve is an electro mechanically functioned valve, which is measured by an electric current through a solenoid. It can be used to regulate the water flow and to measure the level of water. Solenoid valve offers fast and harmless switching, more reliability, lengthy service life, best medium compatibility of the materials used, short control power and compressed design.
NODEMCU
	ESP8266Wi-Fi is enabled with an on chip (SoC) module and employs a 32-bit RISC CPU based on the Tensilica Extensa L106 running at 80 MHz (or overclocked to 160 MHz). It has a boot ROM of 64KB, 64 KB instruction RAM and 96 KB data RAM. External flash memory can be accessed through SPI. The working voltage is 3.3V.
MQTT 
	MQTT is a simple messaging protocol, designed for confined devices with low-bandwidth. So, it’s the right answer for Internet of Things packages. MQTT lets in you to send commands to govern outputs, study and post data from sensor nodes and much extra. Therefore, it makes it virtually smooth to set up a verbal exchange between more than one device. In MQTT there are some simple principles which you want to apprehend: Publish/Subscribe, Messages, Topics and Broker. MQTT – Publish/Subscribe protocol. The first concept is the put up and subscribe device. In a publish and subscribe system, a device can post a message on a topic, or it may be subscribed to a specific topic to get hold of maximum packet size is 256MB. Small packets have 1-byte packet length field if its packet field is less than 127 bytes less than 16383 will use 2 bytes.


Relay Modules
Relay modules use low-level data signals to switch relays capable of handling loads up to 10 Amps. Ideal for devices like PIR detectors and other sensors that output low level signals that need to turn another device on or off. Great for use with Arduino and other microcontrollers. Onboard LED indicators light when a relay is switched. Convenient screw terminals for relay outputs. 0.1" header for voltage and signal input. Available in 1, 2 and 4 relay configurations.
Scalability-
Cloud Computing- We can upload as much data as we want, so this is the best solution for our problem statement. Whereas in Fog Computing the data is pushed to the edges of the cloud
It can also be implemented in the big irrigation plots of factories of industries where water requirement is at the most 
Feasibility
•	We can completely rely on the technology we are using.
•	Cost effective
•	Best performance
•	Reliable
Impact
It gives us the perfect blend for our problem as latest technologies have been used
IoT Cloud
Relevance
This is completely relevant and perfect solution for our problem
