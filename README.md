**first function in separate repo**  
https://github.com/PatrikRindlisbacher/grbl-Status-light-tower-M5-Atom-Matrix  
!!!! The Light Tower is already supported by 3 boards.




# FluidNC or GRBL UART-Gateway and I/O-Module or external Display
Universal Extension via UART for pendant, external screen or input buttons or LED ....

![image](https://user-images.githubusercontent.com/39780457/222853536-45064344-fa95-4174-96e7-7ad30469f224.png)

Flow of functions:
- continuous sending of character ?
- receive all messages from CNC controller
- Message type recognition
- parse message
- Provide all values in variables
- Individual evaluation of the values

**This project was born on 02/15/2023. --> Today, Feb. 20th, I will put the first part online.**  
https://github.com/PatrikRindlisbacher/grbl-Status-light-tower-M5-Atom-Matrix

It should support GRBL from the current version 1.1
https://github.com/gnea/grbl/wiki/Grbl-v1.1-Interface

Tests are already running with an ESP32 from M5Stack (Core2 / Atom )


Projects that could be exciting.
https://github.com/grblHAL/grblHAL_MessageParser
https://github.com/AC8L/FluidNC-Pendant  
https://github.com/gjkrediet/Fluid-controller  
https://github.com/quezadaminter/GrblJogCtrl  
http://dangeroustools.com/2020/01/03/dro-and-jog-wheel-for-grbl/  
https://openbuilds.com/builds/interface-cnc-touch-control-system.9688/  

