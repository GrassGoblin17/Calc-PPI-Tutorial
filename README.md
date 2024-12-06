# Calc-PPI-Tutorial
## Jace Turner
#### A breif tutorial on how to **calculate PPI**, by reading you should have a basic understanding on how to calculate PPI **(Pixals Per Inch)**
###### Tutorial for anyone trying to calculate PPI

First you need to have the width and height in inches, if you are given cm or mm convert this to inches. 
With these numbers insert them into (diagonal = square root of width squared + height squared) this will give you the *diagonal in inches* keep track of this number

Next we need to find the diagonal in pixels. This is the same equation as the diagonal in inches (diagonal = square root of width squared + height squared) simply plug in the pixel amounts to this to get your *diagonal in pixels*

Once we have these two numbers you can calculate the PPI by dividing your diagonal in pixels by your diagonal in inches. 

## EXAMPLE

**Screen size** is 21mm by 28mm
**Resolution** is 640x480

first convert mm to inches to get 0.826772 by 1.10236
then plug them into the equation $\sqrt{.826772^2 + 1.10236^2}$
this gives you **1.3779512** this is your *diagonal in inches*

then plug in the Pixels $\sqrt{640^2 + 480^2}$
this gives you **800** this is your *diagonal in pixels*

Lastly to get you PPI you will plug in your two numbers 800/1.3779512 
this gives you your PPI of 580.57208412
