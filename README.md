Smart-Classroom-
We are going to made a smart classroom by using Arduino. Our project has 3 parts 

1. Smart lights
2. Smart fans  
3. Fingerprint door lock
# Smart Lights and Fans:
We are making this system to reduce consumption of energy.This system will work
On basis of motion, when someone will enter the room the smart system will automatically 
work and LCD will display how many persons in the room.
# Hardware installation:
we will need the following components:
Arduino Uno
ultra sonic sensors hc-sr04x2
jumper wires
1 channel relay
led display 16x2
100R resistor !

4.7k resistor
1k resistor
bulb holder!

220v LED Bulb

5v 2 2Amp power Adapter
# working
First of all connect sensors with Arduino for input:
1.Connect echo and treg pin of 1st sensor to pin A0 and A1 pin of arduino
2.Connect gnd and vcc pin of sensor to arduino
3.Connect echo and treg pin of 2nd sensor to pin A2 and A2 pin of arduino
4.Connect gnd and vcc pin of sensor to arduino
Now going towards output we have to connect LCD with arduino
1. D4 of LCD to 4th digital pin of Arduino 
2. D5 of LCD to 5th digital pin of Arduino 
3. D6 of LCD to 6th digital pin of Arduino 
4. D7 of LCD to 7th digital pin of Arduino 
#Introduction
This part contain a smart door lock with fingerprint interface. This is an Arduino compatible fingerprint module with the high speed DSP processor. This fingerprint module could work alone without any principal computer or any PC software. It could store 1000 fingerprints. Support fingerprint entry, intelligent image processing, finger print comparison and fingerprint search mode. It also has a high sensitivity to both wet and dry fingerprint recognition.
#Working principal
Fingerprint processing includes two process: fingerprint login process and fingerprint matching process. When fingerprint login each enter two times, will two the second entry image is processed, and the composite template is stored in the module. When the fingerprint is matched through the fingerprint sensor the image to be verified entered and processed then matched with the fingerprint template.
Devices 
For the implementation of this project we will be using a fingerprint sensor, arduino,breadboard,solenoid door lock, LCD 16x2.
![68747470733a2f2f312e62702e626c6f6773706f742e636f6d2f2d37487634667248316d70342f5850447a323051757775492f41414141414141425153492f6841456c556247386b48305855554432556a744758684f42464d4a53665a503167434c63424741732f733634](https://user-images.githubusercontent.com/126908875/222804031-3598f8cf-9b85-439e-a223-18fc653eb074.png)

5. E of LCD to 3rd digital pin of Arduino
6. Rs of LCD to 2nd digital pin of Arduino 
7. Ground the following pins of the LCD:
  A). K![68747470733a2f2f312e62702e626c6f6773706f742e636f6d2f2d57564b744b466f6341724d2f5850447a336e7468464a492f41414141414141425153512f6f446c47384169636a577356614e5368766f6158656678466f5937487453363677434c63424741732f733634](https://user-images.githubusercontent.com/126908875/222803838-f07bf028-1cf6-4375-ab04-0dff77050b21.png)
![68747470733a2f2f312e62702e626c6f6773706f742e636f6d2f2d6f474365685972615a42632f5850447a323078654a7a492f41414141414141425153452f743544493938716f6871675645374964655878444873616662384a4d4555454e67434c63424741732f733634](https://user-images.githubusercontent.com/126908875/222803950-109a96d7-b324-4e14-8739-c422ed0d0556.png)

  B). RS
  C). Vss
10. Vcc the following pins:
11. A). A
12. B). VDD
13. C). VO
14. Connections of Relay:
15. IN  pin of relay to 8th digital pin of Arduino.
16. vcc to 5v
17. GND to GND
18. COMMON PIN to directly Bulb/Fan.
19. NORMAL CLOSE to directly 220v.


#Introduction
This part contain a smart door lock with fingerprint interface. This is an Arduino compatible fingerprint module with the high speed DSP processor. This fingerprint module could work alone without any principal computer or any PC software. It could store 1000 fingerprints. Support fingerprint entry, intelligent image processing, finger print comparison and fingerprint search mode. It also has a high sensitivity to both wet and dry fingerprint recognition.
#Working principal
Fingerprint processing includes two process: fingerprint login process and fingerprint matching process. When fingerprint login each enter two times, will two the second entry image is processed, and the composite template is stored in the module. When the fingerprint is matched through the fingerprint sensor the image to be verified entered and processed then matched with the fingerprint template.
Devices 
For the implementation of this project we will be using a fingerprint sensor, arduino,breadboard,solenoid door lock, LCD 16x2.
