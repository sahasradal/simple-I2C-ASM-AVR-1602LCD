# simple-I2C-ASM-AVR-1602LCD
simple ASM program to send data to 1602 HITACHI LCD from AVR ATTINY13 or Attiny10
I2C working program to display "hello" on 1602 Hitachi LCD , I used Attiny13A with Pb1 & PB0 as scl & sda   
used above chip with PCF8574T i2c backpack 1602 hitachi compatible chinese made LCD from aliexpress.          
code as it is occupies 640 bytes=62.5% of code space. one can get rid of the hello write to save space.             
The skeleton of this code was taken from Kodera2t's Attiny10 bitbang posted in git & Hacker.io                    
He used push pull and I changed it to open drain commands for SDA & SCL                                      
The delay subroutines were taken from 4 bit LCD code written by Donald Weiman    (weimandn@alfredstate.edu)        
Grattitude to the neumerous individuals who have posted on the internet from which I have taken shamelessly.        
I took it from the internet and put it back in the internet,                                                   
To whomesoever it may be useful. Best wishes SAJEEV SANKARAN.
use pull up resistors 4.7k on both SDA & SCL. I personally used 5k as i didnt have the 4k7 ones.
This code only sends to a slave and mimics I2c protocol with software.
this is my first serious code after LED blink.Please forgive my ignorance if you see any bad coding and by profession I am a car mechanic and found assembly easy
to understand as it is just placing things on a list for the MCU to do. 
