# smart_baggage_tracker
tracking the live location of the bag using IoT




A smart baggage tracking system using an Arduino Uno, GSM and GPS modules, and a Wi-Fi module combines hardware and software to monitor and track luggage throughout its journey. The Arduino uno serves as the microcontroller and is responsible for data collection, processing, and communication with other modules like GSM, GPS, Wi-Fi Modules.

    The baggage tracking device is initialized with passenger and travel information.The GPS 
      module acquires the initial location of the luggage. The system continuously collects GPS data 
      and, if available, sensor readings (temperature, humidity, etc.) to monitor the luggage's status.

The system decides which communication method to use (GSM or Wi-Fi) based on the availability of network coverage. When in a cellular network area, the system uses the GSM module for communication.

Using the selected module (GSM or Wi-Fi), the system sends data to the central server, including GPS coordinates, sensor data, and flight details.

The central server receives and processes the data from the luggage tracker. It updates the luggage's location, analyzes data, and maintains a database of luggage and passenger information. They receive notifications and updates about their baggage's status throughout the journey.

output :
a msg has be recieved from the sim800l with map location.
![WhatsApp Image 2024-01-31 at 2 02 09 PM (1)](https://github.com/k0Arjun/smart_baggage_tracker/assets/155369438/11055894-4205-42f9-993a-051cb21466a1)

using the link we will be able to locate the perfect location by using it.
![WhatsApp Image 2024-01-31 at 2 02 09 PM](https://github.com/k0Arjun/smart_baggage_tracker/assets/155369438/6d86e660-528b-40c8-ab71-6bfd228dff97)


circuit connection:

By connecting Gps, Gsm and arduino together with proper , we have made tracking system for smart baggage application . The following figure shows the circuit connection of the smart baggage tracking system





