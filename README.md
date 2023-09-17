# Smart Home System project description
this project is made to achieve  the idea of the smart home system come to real by giving you the control of the whole house in your hand
the project is composed of 3 main parts :
1- Guest 
2- owner
3- the AC/lightnening control system 
![The Full Project](https://github.com/youssef-7atem/projects/assets/141189859/c01c0774-37d0-44f0-b25b-220d59286a43)
1- The first part is Guest part where when some one comes infront of the door when the buzzer is pressed the lcd infront of him gives him options after talking some orders from the owner whether the doors unlocks him self by rotating the motor automaticaly and closing the door once the guest enters 
other options is the guest to be given the guest password where he can enters the house for 1 time and then the passwords changes 
another option if the guest was already a member of the onwers house he can enter the owners password and then he will premitted to open the door 
2-second part  owner part where he controll the smart door and who enters and leaves the house 
 
![Owner_Guest](https://github.com/youssef-7atem/projects/assets/141189859/dac1aa87-d4dd-4d89-af55-b5c557e63560)

3- part 3 is the owner controlling every light in the home and the air conditing system using a temprature sensor to activate the ac when the temprature is too cold or too hot and measure the current room temp 

![Light](https://github.com/youssef-7atem/projects/assets/141189859/43775b3c-a56f-4c1c-b937-43a99c29a3ad)


Components :
- 3 ATmega32 microcontroller
- 3 keypad 4*4
- 2 LCD 2*16
- switch (DIP)
-LM35 Temperature Sensor
-LDR Light intensity sensor
- Motors & LEDs& resistances
-Servo Motor
-buzzer & speaker

The system have:
log in system
LDR system
Door
Buzzer system
Control 4 rooms
Control air conditioner in 2 modes related to the temperature measured by temperature sensor or using that button

Drivers used:
-BIT_MATH LIB 
-STD_TYPES_LIB
-DIO DRIVER
-ADC DRIVER
-LCD DRIVER
-KPD DRIVER
-TIMER1 DRIVER
-UART DRIVER
-Alarm DRIVER
-DELAY DRIVER
