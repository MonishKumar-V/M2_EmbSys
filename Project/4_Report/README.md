## Temperature Controlled Fan :

## Introduction :

The main intention behind this temperature controlled fan is to automatically control the speed of the fan based on the room temperature variations. 

we will be able to adjust the fan speed in our home or office according to the room temperature and also show the temperature and fan speed changes on a LCD display. 

Temperature sensor is used to read the room temperature and it is sent to the ADC to convert the analog signal to digital signal. This signal is sent to micro-controller and it processes the input and the fan speed is adjusted with the help of actuators. The Temperature reading and the respective fan speed is displayed on the LCD display. 

## Requirements :
 
 ## High Level Requirements :
 
|ID|High Level Requirements|Status
|--|--|--|
|01  |It shall have the ability to sense temperature.  |To be done.
|02|It shall have the ability to Control the fan.|To be done.|
|03|It shall have the ability to measure the speed of the fan.|To be done.
|04|It shall have the ability to display.|To be done.

## Low Level Requirements :

|ID|Low Level requirements |Status
|--|--|--|
| 01 |It shall have temperature sensor. |To be done.
|02|It shall have a relay. | To be done.
|03|It shall have a speed sensor.| To be done.
|04|It shall have a LCD display.|To be done. 


## Block diagram :



![Blank diagram (1)](https://user-images.githubusercontent.com/75168665/155832403-cdbb5d77-a565-4847-9b53-86b2c89cb73b.jpeg)


## Description :

 -  **User Input** : The User can provide input to the micro controller using this, in this case the user provides temperature to the system.
 - **Temperature Sensor** : This sensor is used to measure the room temperature and it is fed to the micro controller via ADC.
 - **ADC** : This components, as the name indicates, is used to convert analog to digital signal and is fed to micro-controller.
 - **Micro controller** : It controls the whole operation the embedded system.
 - **Speed Sensor** : It is used to measure the speed of the fan and fed to the display via micro controller.
 - **Relays** : It is connected with the micro controller to help adjust the fan speed according to the instruction.
 - **LCD display** : It displays the temperature and the respective fan speed.


## Application :

 -   Temperature  based  fan  speed  controller  is  useful  for  cooling the  processor  in  the  laptops  and  personal  computers more efficiently. Generally  fan  in  laptop  comes  with  only  two  or three possible speeds. So it results in more power consumption.
 -   The  fan  designed  in  this  project,  has  different  values  of speed  according  to  temperature  change.  This  can  be  also  used  in small  scale  industries  for  cooling  the  electrical/mechanical equipment. 
