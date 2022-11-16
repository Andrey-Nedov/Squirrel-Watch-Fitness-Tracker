# Smartwatch with fitness tracker functions
<img src="/imgs/im6.png" width="800"/>

*01.01.2016 - 30.07.2017*  [![Generic badge](https://img.shields.io/badge/Status-Closed-red.svg)](https://shields.io/)<br/>

*Team*
1. [Andrey Nedov](https://github.com/Andrey-Nedov-is-a-human) (16 y.o. hardware, software, manager)
2. Egor Vasilenko (15 y.o. mobile app programmer)
3. Michail Onegin (15 y.o. 3D-designer)
<br/>

## Objective of the project
The goal of the project was to create a simple fitness tracker with the ability to sync with a smartphone to display notifications on the tracker.

<img src="/imgs/im7.png" width="700"/>
<img src="/imgs/sm.gif" width="700"/>

## Realization

### Watch

The device is based on an Atmega328p AVR microcontroller in a compact SMD package. Synchronization with a smartphone is provided by the Bluetooth module built into the watch. Information about the distance traveled is taken from the GPS module of the smartphone. The device also has a vibration motor for feedback.

<img src="/imgs/3d.gif" width="700"/>

The layout of the main board was modeled in the SprintLayout program, then it was transferred to a textolite by the laser-ironing method, which then floated to be etched into iron chloride.

<img src="/imgs/im8.png" width="600"/>
<img src="/imgs/im9.jpg" width="600"/>
<img src="/imgs/im10.jpg" width="600"/>
<img src="/imgs/im11.jpg" width="600"/>
<img src="/imgs/im12.jpg" width="600"/>

Next, SMD components were soldered onto the board.

<img src="/imgs/im13.jpg" width="600"/>

*Result*

<img src="/imgs/im14.jpg" width="800"/>

### Mobile application

The application was developed using the Cordova framework using plugins for working with Bluetooth and GPS modules, as well as access to incoming calls and SMS notifications.
<p>
<img src="/imgs/im1.jpg" width="150"/>
<img src="/imgs/im2.jpg" width="150"/>
<img src="/imgs/im3.jpg" width="150"/>
<img src="/imgs/im4.jpg" width="150"/>
<img src="/imgs/im5.jpg" width="150"/>
</p>

<br/>
<br/>

## Conclusion

<img src="/imgs/os.gif" width="700"/>

Having produced a minimal working prototype, the team decided to close the project, leaving the hull fabrication.
The team successfully performed at scientific and practical conferences and went on vacation with dignity.
