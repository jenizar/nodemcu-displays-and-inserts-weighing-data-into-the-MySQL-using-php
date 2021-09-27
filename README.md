# nodemcu-displays-and-inserts-weighing-data-into-the-MySQL-using-php
nodemcu displays and inserts weighing data into the MySQL database using the php program

materials:

digital hanging scale custom, nodemcu load cell amplifier high quality HX711, adaptor 5v/3A, jumper cable.

![alt text](https://github.com/jenizar/nodemcu-displays-and-inserts-weighing-data-into-the-MySQL-using-php/blob/main/loadcell_php_web.PNG)
![alt text](https://github.com/jenizar/nodemcu-displays-and-inserts-weighing-data-into-the-MySQL-using-php/blob/main/loadcell_data_web.PNG)
![alt text](https://github.com/jenizar/nodemcu-displays-and-inserts-weighing-data-into-the-MySQL-using-php/blob/main/digital_hanging_scale.jpg)
![alt text](https://github.com/jenizar/nodemcu-displays-and-inserts-weighing-data-into-the-MySQL-using-php/blob/main/digital_hanging_scale_nodemcu_hx711.jpg)
![alt text](https://github.com/jenizar/nodemcu-displays-and-inserts-weighing-data-into-the-MySQL-using-php/blob/main/nodemcu_hx711_loadcell_amplifier.jpg)
![alt text](https://github.com/jenizar/nodemcu-displays-and-inserts-weighing-data-into-the-MySQL-using-php/blob/main/portable_digital_hanging_scale.jpg)

instructions: 

A. digital hanging scale to HX711 load cell amplifier
1. disconnect the cables connecting the scale sensor (green-white-red-black) to the modified scale display board. Then solder the cables to the PCB
2. use a mouse cable or a former speaker cable with a length of 1 - 1.2 meter to and connect the 4 cables to the PCB that has been soldered at number 1.
3. the weighing case is punched at the top so that the 1 meter long cable can come out
4. disconnect the cable connected to the battery on the modified scale display panel board.
5. lastly, close the case gently tighten the bolt nut; make sure the position of the component parts remains the same when first opened.
6. match the 4 wires coming from the weighing sensor to the load cell amplifier HX711 red - red, black - black, white - white, green - green
7. Adjust the 4 pins on the HX711 load cell amplifier with the pins on the Arduino board. VCC - 5v, DAT - D5, CLK - D6, GND - GND

[![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/h56QFyca2MI/0.jpg)](http://www.youtube.com/watch?v=h56QFyca2MI)

references:
1. https://github.com/jenizar/arduino-digital-hanging-scale-data-on-p10-led-panel
2. https://randomnerdtutorials.com/esp8266-nodemcu-http-get-post-arduino/
3. https://youtu.be/ow3bfegsCyM


