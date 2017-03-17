# maRIO
A program to control remotly a robot, with a NI myRio, a PC or an Ipad via wifi, and done under Labview and the National Instrument app. This project was done at the end of my bachelor degree, in a team a 5 person that I led. I also did 90 % of the code you can see here, as the woodworking necessary.

# Demo


![Demo](https://cloud.githubusercontent.com/assets/25333848/24050251/8daa6d4c-0b2e-11e7-98cc-053ac0097eb5.gif)

# Installation

## General
If you want to reuse this code, be free to do so.  

To reusse this programm you will have to change the different UART values uses throughout this programm to match your motordriver commands, with the one I used in my case. Which is a MD49 and you can find the documentation for it here : http://www.robot-electronics.co.uk/htm/md49tech.htm

## Different keyboard
To accomodate to a  QWERTY keyboard or other, simply change values picked by  `Keyboard_mode.vi` .
And to make the core function works for your own change the bit frame picked by the different SubVi contained in the MyRio SubVi directory. 
