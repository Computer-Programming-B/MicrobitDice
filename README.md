micro:bit Dice
--------------------
In this assignment you will program your micro:bit to simulate a single die cube. When you shake your micro:bit it will generate a random pattern of dots from 1 to 6. You may find slides 58 - 69 of the [slide presentation](https://docs.google.com/presentation/d/1aiGcnPn8uoCJdX8p7_qoI3Hh3_KOhUtFeB3Byw0tacA/edit?usp=sharing) helpful in completing this assignment. Here is a simple program that displays an image of a confused face for 1 second when the micro:bit is shaken:
```python
from microbit import *
import random

while True:
    display.clear()
    if accelerometer.was_gesture('shake'):
        display.show(Image.CONFUSED)
        sleep(1000)
```

Program requirements
-----------------
* Your program must use at least 6 images that you create to show the number of dots that were rolled
* Your program must use the Python `randint()` function
* Your program will need at least one variable to store the random number of dots
* Your program will need a number of `if` statements to select the right image based on the number in the variable
* Submit both the Python code and an animated gif showing your program running to Google Classroom

Random Numbers in Python
------------------------
Python has a module (part of a larger collection of code called a "library") with a number of useful functions for random numbers. To use this module you need to add `import random` at the top of the program (see the sample code with a confused face above). For this assignment, we'll use the `randint()` function which takes two arguments:   
`random.randint(a, b)`  
It return a random integer between a and b inclusive.   

Suggested steps to completing this assignment
----------
1. Start with the sample program above
2. Between lines 10 and 11 create a variable `dots` and initialize it to a random number between 1 and 6. Make sure the code is indented so that it "belongs" to the `if accelerometer.was_gesture('shake'):`
3. Replace `display.show(Image.confused)` with an `if` statement that checks to see if `dots` is equal to 1. Underneath, display an image with one dot. Be sure to indent the `display` so that it belongs to the `if` statement.
4. Add 5 more if statements for the numbers 2 - 6

Extensions
----------
You can add animations to make "rolling the dice" more dramatic. You could also simulate dice with different numbers of faces like the dice used in Dungeons and Dragons.

Samples of Student Work
----------
[Yangyang](Yangyandice.gif)   
[Allison](AllisonDice.gif)   
[Jordan](JordanDice.gif)   
[Cali](CaliDice.GIF)   
[Emerson](EmersonDice.gif)   
[Sandy](StephanieDice.gif)   
[Cilla](CillaDice.GIF)   
[Isaac](IsaacDice.GIF)   
[Stephanie](StephanieDice.gif)   
[Linen](LinenDice.GIF)   
[Jasmine](JasmineDice.gif)   
