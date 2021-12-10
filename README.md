micro:bit Dice
--------------------
In this assignment you will program your micro:bit to simulate a single die cube. When you shake your micro:bit it will generate a random pattern of dots from 1 to 6. Here is a simple program that displays an image of a confused face for 1 second when the micro:bit is shaken:
```python
while True:
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
Python has a module (part of a larger collection of code called a "library") with a number of useful functions for random numbers. To use this module you need to add `import random` at the top of the program. For this assignment, we'll use the `randint()` function which takes two arguments:   
`random.randint(a, b)`  
It return a random integer between a and be inclusive.   

Suggested steps to completing this assignment
----------
1. TBD 

Extensions
----------
You can add animations to make "rolling the dice" more dramatic. You could also simulate dice with different numbers of faces like the dice used in Dungeons and Dragons.

Samples of Student Work
----------
*none yet!*
