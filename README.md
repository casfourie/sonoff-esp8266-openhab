# sonoff-esp8266-openhab
Main online resource for this projects was https://www.superhouse.tv/17-home-automation-control-with-sonoff-arduino-openhab-and-mqtt/

Main Learnings

Install Additional Binaries
https://github.com/esp8266/Arduino

OpenHAB + MQTT + InfluxDB Install on Raspberry Pi from scratch
https://www.youtube.com/watch?v=-4aRaCAbZxU
After openhab instal run configuration tool "sudo openhabian-config"

Install OpenHab
  Connect to the openHAB 2 dashboard: http://openhabianpi:8080
  Connect to the Samba network shares with username openhabian and password openhabian
  Connect to the openHAB Log Viewer (frontail): http://openhabianpi:9001
  Node-RED - Accessible from http://openHABianPi:1880
  KNXd - KNX daemon running at 224.0.23.12:3671/UDP
  Grafana - available from http://openHABianPi:3000




Install MQTT
Intall Node-Red
Install InfluxDB

some usefull commands
sudo ifdown wlan0  //Wireless interface down
sudo ifdown wlan0  //Wireless interface up
