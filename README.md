# Monte Carlo process

Monte Carlo (MC) methods are a subset of computational algorithms that use the process of repeated random sampling to make numerical estimations of unknown parameters

## Estimate Pi using Monte Carlo
What is it Pi?

![image](https://user-images.githubusercontent.com/71387302/227799191-6653bb53-8aa8-486d-875c-8e602ce51340.png)

The area of a circle is A = πr2
The aera of a square= (2*r)2 ==> 4r2

The area of circle/aera of a square=π/4
π=4*(area of circle/aera of a square)

we can also compute pi as folowing:
1. Choose 2 random floats between -1 to 1 (x and y).
2. If x2+y2>=1 then count it in the circle area.
3. Repeat this trial N times
4. Estimate pi as folowing: π=4*(count of points in the circle area/sum of all points)

As N get bigger- the estimation of π is better:


