# hw3

setting:

connect the uLCD to the mbed.
open screen on terminal.
LED1 represents the execution of GestureUI.
LED2 shows initialization process for a user to place the mbed on table.
LED3 represents the execution of TILT.

GestureUI:

use the "/GestureUI/run 1 0" to start the GestureUI function.
LED1 turn on.
use the gesture in lab8 to indicate the mbed to increase or decrease the angle on the uLCD. (ring is increase, forward is decrease)
press the "user botton" to confirm the angle we select.
LED1 turn off.

TILT:

use "/TILT/run 1" to start the TILT function.
LED2 turns on.
put the mbed on the table, LED2 will turn off and LED3 will turn on.
start to tilt the mbed, if the angle is higher than the threshold angle, python will print current angle, if it reach 10 times , it will break.
