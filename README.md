# Python Etch-a-sketch game

A simple python program to draw on the screen with keystrokes. I'm using python `turtle` for this


## Controlling the turtle with your keyboard

| Key  | Function |
| ------------- |:-------------:|
| w      | moves the turtle forwards by 20px     |
| s      | moves the turtle backwards by 20px     |
| a      | turns the turtle anticlockwise by 10 degree on each keystroke|
| d      | turns the turtle clockwise by 10 degree on each keystroke|
| c      | clears the screen and moves the turtle to the starting position|

## Initializing the turtle

```
from turtle import Turtle, Screen

tim = Turtle()
screen = Screen()
 
code goes here.

screen.listen()
screen.exitonclick()
```

## Useful Resources
[Turtle documentation](https://docs.python.org/3/library/turtle.html)