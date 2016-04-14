# mqtt_paho_cpp

# Description
Using MQTT Paho examples in C++ for Linux (client subscriber)  
QT Project.

### Notes
Using [Mosquitto](http://mosquitto.org/) as broker and [Paho](http://www.eclipse.org/paho/) for development in C++.

## Usage 
1) Open a broker
```
sudo service mosquitto start 
```
2) Check IP's broker
```
ifconfig
```
3) Open this project in MQTT
  - Change the IP in ADDRESS to your broker's IP (main.cpp)
  - Check the topic in TOPIC (main.cpp)
4) Run
5) Open a terminal and publish
```
mosquitto_pub -h [broker's IP] -t [your topic] -m "Hello MQTT!"
```
6) Or you can use the client publisher example!

## Requirements
- [Install mosquitto](http://mosquitto.org/download/)
- [Build Paho](http://www.eclipse.org/paho/clients/cpp/).

### More info
[debihiga.wordpress.com](https://debihiga.wordpress.com/)
