# Arduino-ultrasonic-sensor-hc-sr04-TEST
Changing the color from your RGB Led Strip by using the ultrasonic sensor.
![Image description](https://cdn-reichelt.de/bilder/web/xxl_ws/A300/DEBO_JT_ESP8266_01.png)

For this tutorial you will need:

- a NodeMCU
- a USB to micro-USB cable
- a unit to power the NodeMCU
- the ultrasonic sensor
- RGB LEDstrip that you can connect to the NodeMCU
-four female jumper wires


## Step 1 - Upload the code

Download the Arduino code file (ArduinoCode.ino) and open it in Arduino, then you upload this to your NodeMCU to control the sensor. Use the USB to micro-USB cable to power the NodeMCU. The NodeMCU is properly connected if a blue LED blinks one time when you plug in the USB. 

## Step 2 - Connect the NodeMCU to the ultrasonic sensor. 

Next you connect the ground from the ultrasonic sensor to the ground from the NodeMCU by using the four female jumper wires. Subsequently you connect VCC on the ultrasonic sensor to the VU on the NodeMCU. Then you need to choose two seperate pins on the NodeMCU to connect the trigger and echo on the ultrasonic sensor. In my code I used pin D1 and D2 on the NodeMCU, in order to make this as easy as possible you can follow me in also using these pins. 

If you require more clarification you can use this video: https://www.youtube.com/watch?v=7nxOZek1iGI that describes the steps clearly.

To check whether you are properly connected you can open the serial monitor and check if you get the correct values from the ultrasonic sensor by moving your hand above the sensor. 
 

## Step 3 - Connect the RGB LEDstrip

Next you will need to connect the ultrasonic sensor to the RGB LEDstrip, you can establish this by connecting the ground from the RGB LEDstrip to the ground from the NodeMCU. Then you connect the bin on the RGB LEDstrip to the selected pin of your choice. In order to make it easier you can follow me by using pin D5. 

To check if the RGB LEDstrip is working accordingly you move your hand above the ultrasonic sensor at different distances, the RGB LEDstrip should then show different colours according to your code. 



