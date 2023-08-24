Smart home automation systems have revolutionized the way we interact with our living spaces. In this system, we present a comprehensive solution for home automation, consisting of fan and light automation, as well as gas and flame detection. The system utilizes advanced sensors and algorithms to detect changes in the environment and respond accordingly, ensuring safety and convenience for the occupants.
The fan and light automation feature allows remote control of these appliances, providing convenient control over the home's environment. The system automatically adjusts the fan speed and light brightness based on the ambient light and temperature, making the home more comfortable and energy-efficient.
The gas and flame detection feature utilizes advanced sensors to detect dangerous levels of gas and alert occupants in case of a potential gas leak. Additionally, the system can detect the presence of flames and send alerts to the occupants, preventing potential fire hazards.

The NodeMCU v1.0 board is a powerful tool for controlling systems remotely through the internet. It is also a microcontroller board that allows interaction with sensors such as the DHT11 and PIR sensors. The DHT11 is a temperature and humidity sensor, while the PIR sensor detects motion. With the help of these sensors, the NodeMCU v1.0 board can determine whether a person is present in a room and what the temperature is. This information can then be used to make decisionsabout whether to turn on the AC or the fan.

The primary objective of using the NodeMCU v1.0 board with the DHT11 and PIR sensors is to achieve energy savings. By detecting the presence of a human in the room, the system can determine when it needs to turn on the AC or the fan. This helps to ensure that energy is not wasted by unnecessarily running the AC or fan when no one is present in the room.

The basic idea is to turn on the fan or AC when a human is detected, based on the temperature in the room. If the temperature is above 22 degrees Celsius, the AC will turn on, while the fan will turn on when the temperature falls below 22 degrees Celsius. To control the fan and AC, two 5V relays are used, which are operated through controlling pins (IN1and IN2, respectively).
The NodeMCU v1.0 board is programmed to read the sensor values continuously. It then processes the data and determines whether the ACor fan needs to be turned on. The microcontroller on the board uses a built-in WiFi module to communicate with the internet. This allows the system to be controlled remotely through a web interface.

The system is built using the NodeMCU v1.0 board, DHT11 and PIR sensors, and two 5V relays. The NodeMCU v1.0 board is mounted on a breadboard along with the sensors and relays. The DHT11 and PIR sensors are connected to the board through their respective pins. The 5V relays are also connected to the board through their respective pins. The AC and fan are connected to the relays, which are used to turn them on and off.

The NodeMCU v1.0 board can be programmed using the Arduino IDE. The code needs to be written to read the sensor values, process the data, and control the relays. The system also needs to be connected to the internet to allow remote control. This can be achieved using a WiFi network and a web interface.
