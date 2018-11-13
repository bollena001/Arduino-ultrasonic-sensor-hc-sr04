# Arduino-ultrasonic-sensor-hc-sr04-TEST
![Image description](https://cdn-reichelt.de/bilder/web/xxl_ws/A300/DEBO_JT_ESP8266_01.png)
changing the color from your RGB Led Strip with your ultrasonic sensor.

For this tutorial you will need: 
- four female jumper wires
- the ultrasonic sensor
- the NodeMCU
- a USB to micro-USB cable
- a unit to power the NodeMCU
- RGB LEDstrip that you can connect to the NodeMCU

## Step 1 Connect the NodeMCU to the ultrasonic sensor. 

First you connect the ground from the ultrasonic sensor to the ground from the NodeMCU by using the four female jumper wires. Subsequently you connect VCC on the ultrasonic sensor to the VU on the NodeMCU. Then you need to choose two seperate pins on the NodeMCU to connect the trigger and echo on the ultrasonic sensor. In my code I used pin D1 and D2 on the NodeMCU, in order to make this as easy as possible you can follow me in also using these pins. 


If you require more clarification you can use this video: https://www.youtube.com/watch?v=7nxOZek1iGI that describes the steps clearly. 

## Step 2 Connect the RGB LEDstrip

Next you will need to connect the ultrasonic sensor to the RGB LEDstrip, you can establish this by connecting the ground from the RGB LEDstrip to the ground from the NodeMCU. Then you connect the bin on the RGB LEDstrip to the selected pin of your choice. In order to make it easier you can follow me by using pin D5. 

## Step 3 Upload the code
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo 


