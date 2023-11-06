# ArduinoFirstProject

➢ LED on for one second (the 1 second time interval will be 
achieved by using a uC timer). (1p)
➢ LED on/off via serial communication. The letter "A" sent from the PC 
will turn on the LED and the letter "S" will turn off the LED. (1p)
➢ An LED will light up when the temperature at the temperature sensor exceeds 
the threshold of 35 degrees. The LED will turn off when the temperature drops 
below 35 degrees. It will be implemented with a hysteresis of 0.5 degrees. (1p)
➢ A dimming LED will light up. For this, a PWM signal will be used 
with the following 4-second scenario run in a repetitive loop. The 
scenario divided into 4 seconds is as follows: (1p)
a. The LED will perform a linear FADE IN effect for a duration of one
seconds.
b. It will stay on for one second.
c. It will perform a linear FADE OUT effect for one second.
d. It will be off for a second.
➢ It will measure the temperature from an LM35 temperature sensor, 
or similar, which it will send to the PC via the serial interface. (1p)
➢ It will control a 7-segment display and display the initials of the student's 
name. (1p)