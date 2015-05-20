# SIGFOX_ARDUINO
Arduino code to control an AT command SIGFOX compatible evaluation board

The Arduino code is very simple and allow you to modify it in order to do the PoC you want. The PIN on the Arduino has been identified for the Uno board. You might have to adapt the following instructions based on the Arduino board you are using.

Open a new sketch in the Arduino IDE and past the .ino code in the github repo.

This code will send an AT command to the EVB to send a message with the value “66” every 5s to the SIGFOX network. 

AT$SF is a generic command and should work for most evaluation board compatible SIGFOX that implemented AT commands.
The PIN selection is for the Arduino Uno and you will need the Tx PIN to be a DIGITAL PWM PIN.

You can check SIGFOX @ http://sigfox.com/




