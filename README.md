# smart_baggage_tracker
tracking the live location of the bag using IoT




A smart baggage tracking system using an Arduino Uno, GSM and GPS modules, and a Wi-Fi module combines hardware and software to monitor and track luggage throughout its journey. The Arduino uno serves as the microcontroller and is responsible for data collection, processing, and communication with other modules like GSM, GPS, Wi-Fi Modules.

    The baggage tracking device is initialized with passenger and travel information.The GPS 
      module acquires the initial location of the luggage. The system continuously collects GPS data 
      and, if available, sensor readings (temperature, humidity, etc.) to monitor the luggage's status.

The system decides which communication method to use (GSM or Wi-Fi) based on the availability of network coverage. When in a cellular network area, the system uses the GSM module for communication.

Using the selected module (GSM or Wi-Fi), the system sends data to the central server, including GPS coordinates, sensor data, and flight details.

The central server receives and processes the data from the luggage tracker. It updates the luggage's location, analyzes data, and maintains a database of luggage and passenger information. They receive notifications and updates about their baggage's status throughout the journey.

circuit connection:

By connecting Gps, Gsm and arduino together with proper , we have made tracking system for smart baggage application . The following figure shows the circuit connection of the smart baggage tracking system






