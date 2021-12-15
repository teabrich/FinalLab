# FinalLab
UltraSonic Eyes

Amelia and I were motivated to create another version of ultrasonic eyes that we found the Aruino page. Our plan was to use an Arduino nano and program the ultrasonic sensors to trigger the 8×8 LED eyes to track movement. We originally were going to use a 3D printer to make the body for our project but because of a lack of time we decided to use a cardboard box and cut out the appropriate sized holes for the LEDs and ultrasonic sensors. 

To set up the the project, first  place the Arduino MRK 100 on the breadboard, then connect a black wire from from the GND port on the MRK to the GND rail of the breadboard then do the same with a red wire connecting the 3V MRK to the power rail on the board. You then connect a black wire between the two GND rails on the opposite side of the board as well as a red wire connecting the two power rails. 

To connect the ultrasonic sensors you connect the GND pins on the sensors to the GND rail with a black wire and use red wires to connect the power pin from the sensor to the power rail on the board. Finally you connect a white wire from the TRIG pin on sensor 1 to digital pin 2 on the Arduino. Blue wire from the ECHO pin on sensor 1 to digital pin 3 on the Arduino. White wire from the TRIG pin on sensor 2 to digital pin 4 on the Arduino. Blue wire from the ECHO pin on sensor 2 to digital pin 5 on the Arduino.

To connect the two LED matrix displays, connect a black wire from one of the LED matrix GND pins to the GND rail on the breadboard and the same with a red wire connecting the power pin on the LED to the power rail on the breadboard. Then use 5 different colored wires to connect the LED that isnt connected to the breadboard to the one one that is. To connect the rest of the first LED to the breadboard you connect a yellow wire from the SCK pin to pin 13 on the arduino. Connect a blue wire between the pin to digital pin 11 on the arduino and connect a white wire from the CS pin to digital pin 10. That’s the end of the connecting the LEDs. 

The last part of set up will let the LDR detect wether the environment is light or dark around the Arduino and use that information to brighten or dim the LED eyes accordingly. To do this, connect the LDR across 2 rows of pins on the breadboard, connect the resistor between one row of pins on one side of the LDR and GND rail, connect a red wire to the other side of the LDR to the power rail and then finally connect a brown wire between the row of pins the resistor is on and A5 pin on the Arduino. After all of this is finished, you can connect the whole set up to your computer using a USB-micro B to connect to the Arduino and run it in Arduino with the code.  

After everything was set up and worked, there were only a couple things we would tweak. In the tutorial we followed they used an Arduino nano for their project but we didn’t have access to one se we ended up using a Arduino MKR1000, this could’ve been the reason we ran into a couple issues throughout the project and with the end product but I’m not exactly sure about that. Although our project works as its supposed to,the sensors aren’t as sensitive as we hoped they would be, it only catches some movement and we aren’t 100% on it looking different directions. One thing I learned while doing this project is how to properly wire a bread board with the light sensors to that they operate to the best of their ability. I also haven't done a hands on project in a logn time, so creating the box molding for the face like figure was super intresting and had me measurign and cutting out holes with an exacto knife.

Working together with Amelia worked really well. We split up the work evenly, and did all of our work in lab together so we were both always doing something that needed to be done. Together we set up and connected the wires and while Amelia was soldering I finished the wires and while she coded I created out object/face by measuring out and cutting the holes needed for the LEDs and sensors and covered the box in duct tape. Then we commented the code out together, assembled the entire project and stuck the breadbox with all the wires to the inside of the box to hide everything. 
