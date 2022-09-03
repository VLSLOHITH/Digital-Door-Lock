# Digital-Door-Lock
A. DESCRIPTION :
This a door lock using the digital number lock system. Here you need to set a four digit password first using the
number pad and then you can use it as a number lock. When someone is intended to open the door ,they need to press the
password and if it matches the four digit password we set earlier and then the signal is set to on the motor which opens the
door. You are able to reset the password to another four digit number any time using the reset button. This process is done
and checked in a simulator in simulation form.(Note: You can only set 4 digits as a password).
B. Apparatus(used in simulation) :
● Or gates
● And gate
● IC 74Ls95(shift registers)
● Push buttons
● Connecting wires
● DC Voltage sources
● L.E.D’s
● Resistors
● Xnor gates
● Hexadecimal to binary convertor
● DC motor
● 1:2 Demux
● npn transistors
● Switch
● Ground
C.PREPARATION :
Here in this project we use four major digital components.
1) Encoder(1) , 2) Shift register , 3) Encoder(2) , 4) Verifier.
1. <Encoder(1)>
The Function of Encoder here is to convert the decimal numbers to binary numbers by using the ‘or gates’. When we press
the respective button the signal will be set to the respective output pins in Binary form.
In this part we use Push button switches as numbers from one to nine , ‘or gates ‘ ,connecting wires , Dc voltage source.
Truth table
“Input” “Output”
1 2 3 4 5 6 7 8 9 D C B A
1 0 0 0 0 0 0 0 0 0 0 0 1
0 1 0 0 0 0 0 0 0 0 0 1 0
0 0 1 0 0 0 0 0 0 0 0 1 1
0 0 0 1 0 0 0 0 0 0 1 0 0
0 0 0 0 1 0 0 0 0 0 1 0 1
0 0 0 0 0 1 0 0 0 0 1 1 0
0 0 0 0 0 0 1 0 0 0 1 1 1
0 0 0 0 0 0 0 1 0 1 0 0 0
0 0 0 0 0 0 0 0 1 1 0 0 1
A = 1 + 3 + 5 + 7 + 9
B = 2 + 3 + 6 + 7
C = 4 + 5 + 6 + 7
D = 8 + 9

