# AVR_programs
These are for atmega328p


* First you need to add "__AVR_ATmega32U4__" line on your "defines"


![alt text](https://github.com/Nabilislam722/AVR_programs/blob/main/Screenshot%202025-01-07%20162148.png)



* Change avrdude COM port   (--Defult is COM8--)

    -avrdude -F -V -c arduino -p ATMEGA328P -P `COM8` -b 115200 -U flash:w:led.hex
