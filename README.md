# Python-import-turtle-Advance-Art-102
Create python use import turtle graphics code
import turtle as t 
t.bgcolor('black')
t.speed(5)
t.pensize(2)
color = ('orange','white','green')
c=0

for i in range(50):
    t.forward(i*10)
    t.right(144)
    t.color(color[c])
    if c == 2:
        c=0
    else:
        c+=1

t.done()

