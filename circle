import random 
from turtle import Turtle,Screen


timmy=Turtle()

screen=Screen()
timmy.shape('turtle')
timmy.pencolor("green")


colours = ["CornflowerBlue", "DarkOrchid", "IndianRed", "DeepSkyBlue", "LightSeaGreen", "wheat", "SlateGray", "SeaGreen"]


timmy.color(random.choice(colours))
timmy.speed('fastest')

def draw(size_of_gap):
    for _ in range(int(360 / size_of_gap)):
        timmy.color(random.choice(colours))
        current_heading=timmy.heading()
        timmy.setheading(current_heading + size_of_gap)
        timmy.circle(100)
draw(5)
screen.exitonclick()
