import turtle

# Screen setup
screen = turtle.Screen()
screen.title("I Love Mahak")
screen.bgcolor("black")

pen = turtle.Turtle()
pen.color("red")
pen.fillcolor("red")
pen.speed(3)

# Heart shape
pen.begin_fill()
pen.left(140)
pen.forward(180)
pen.circle(-90, 200)
pen.left(120)
pen.circle(-90, 200)
pen.forward(180)
pen.end_fill()

# Text in center
pen.up()
pen.setpos(-100,150)   # adjust position
pen.color("white")
pen.write("I Love Mahak", font=("Arial", 10, "bold"))

pen.hideturtle()
screen.mainloop()

