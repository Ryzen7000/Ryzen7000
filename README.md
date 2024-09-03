from turtle import *
import colorsys
bgcolor('black')
tracer (500)

def drow():
    h = 0
    for i in range(100):
        c = colorsys.hsv_to_rgb(h,1,1)
        h += 0.5
        up()
        goto(0,0)
        down()
        color('black')
        fillcolor (c)
        begin_fill()
        rt (98)
        circle(i, 12)
        fd (290)
        fd(i)
        lt (29)
        for j in range(129):
            print()
            


<!---
Ryzen7000/Ryzen7000 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
