# Python-program-to-draw-a-circle-of-squares-using-Turtle
import turtle

x = turtle.Turtle()

def square(angle):
    for i in range(4):
        x.forward(100)
        x.right(angle)
    x.right(10)

for i in range(36):
    square(90)

turtle.done()
