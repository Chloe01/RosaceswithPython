import turtle

def draw_square(some_turtle) :
    for i in range (1,5):
        some_turtle.forward(100)
        some_turtle.right(90)
def draw_circle(some_turtle) :
        some_turtle.circle(120)

def draw_art():
    window = turtle.Screen()
    window.bgcolor ("cyan")
    turtle.position()
    (0.00,0.00)
    turtle.home()
    ##Draw first Rosace (a and b)
    #Create the turtle a - Draws a circle from squares
    a = turtle.Turtle()
    a.shape("circle")
    a.color("white")
    a.speed(8)
    for i in range (1,25):
        draw_square(a)
        a.right(15)
    #change colors
    a.color("cyan")
    window.bgcolor ("white")
    #Create the turtle b
    b = turtle.Turtle()
    b.shape("circle")
    b.color("aquamarine")
    b.speed(8)
    for i in range (1,13):
        draw_circle(b)
        b.right(30)
    #change colors back
    window.bgcolor ("cyan")
    a.color("white")
    b.color("fuchsia")
    ##Second Rosace on the right (d and e)
    #Create turtle d
    d = turtle.Turtle()
    d.shape("circle")
    d.color("white")
    d.speed(8)
    d.goto(240,-250)
    turtle.distance(d)
    240.0
    for i in range (1,25):
        draw_square(d)
        d.right(15)
    #Create turtle e
    e = turtle.Turtle()
    e.shape("circle")
    e.color("fuchsia")
    e.speed(8)
    e.goto(240,-250)
    turtle.distance(e)
    240.0
    for i in range (1,13):
        draw_circle(e)
        e.right(30)
    ##Second Rosace on the right (d and e)
    #Create turtle d
    d = turtle.Turtle()
    d.shape("circle")
    d.color("white")
    d.speed(8)
    d.goto(240,250)
    turtle.distance(d)
    240.0
    for i in range (1,25):
        draw_square(d)
        d.right(15)
    #Create turtle e
    e = turtle.Turtle()
    e.shape("circle")
    e.color("fuchsia")
    e.speed(8)
    e.goto(240,250)
    turtle.distance(e)
    240.0
    for i in range (1,13):
        draw_circle(e)
        e.right(30)
    ##Third Rosace above(f and g)
    f = turtle.Turtle()
    f.shape("circle")
    f.speed(8)
    f.goto(-240,-250)
    turtle.distance(f)
    240.0
    f.color("white")
    for i in range (1,25):
        draw_square(f)
        f.right(15)
    g = turtle.Turtle()
    g.shape("circle")
    g.color("fuchsia")
    g.speed(8)
    g.goto(-240,-250)
    turtle.distance(g)
    240.0
    for i in range (1,13):
        draw_circle(g)
        g.right(30)
    ##Forth Rosace left(h and i)
    h = turtle.Turtle()
    h.shape("circle")
    h.color("white")
    h.speed(8)
    h.goto(-240,250)
    turtle.distance(h)
    240.0
    for i in range (1,25):
        draw_square(h)
        h.right(15)
    #Create turtle j
    j = turtle.Turtle()
    j.shape("circle")
    j.color("fuchsia")
    j.speed(8)
    j.goto(-240,250)
    turtle.distance(j)
    240.0
    for i in range (1,13):
        draw_circle(j)
        j.right(30)
    #change colors
    window.bgcolor("white")
    a.color("cyan")
    b.color("cyan")
    d.color("cyan")
    e.color("cyan")
    f.color("cyan")
    j.color("cyan")
    
    window.exitonclick()

draw_art()
