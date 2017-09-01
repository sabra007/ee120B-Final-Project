# ee120B-Final-Project


My final project for this class is Simon, a game that asks a player to re-enter sequence
displayed on LED. 
I am usingn 5 LEDs to produce random sequences and 5 buttons for user to repeat the sequence. 
The time period is 500 ms for showing the current sequence and 100ms when user is pressing a button.
It has a feature to produce unique sound for each button pressed and when a corresponding LED is lit. 

It will starts with a welcome screen. Then it waits or button press to begin.
Random sequence will be shown on led. 
Player enters the sequence shown on button presses. 
If the player guesses correctly, they will continue to the next level. There will be 7 levels in total. Level 1 will
have a sequence of 3 LEDs. Level 7 will have a sequence of 9 LEDs. Player will have three lives. If the
player does not guess correctly, he will lose one life, and they will retry that level. After three mistakes,
they will start from the beginning.The LCD will show the player the current level and the current lives.
After the player successfully beats Level 7, the game ends.
The game also stores and displays the highest level a player reached.

Componenets used for this project: ATmega1284, LCD display, 5 push buttons, 5 LEDs, power source. 
Programmed with AVR Studio 7.

Sources for C code.
For timer functions, LCD function and  Puls Width Modulator functions are used from lab manuals.

Demo Link
https://www.youtube.com/watch?v=OLF9h_sVTZM
