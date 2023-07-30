# Estimating the value of π using Monte Carlo

The idea is to simulate random (x, y) points in a 2-D plane with domain as a square of side 2r units centered on (0,0). Imagine a circle inside the same domain with same radius r and inscribed into the square. Then we calculate the ratio of number points that lied inside the circle and total number of generated points. Refer to the image below:

<img src="https://github.com/ArtemGrablevski/pi-monte-carlo/blob/main/images/graph.png" width="400" height="400">

We know that area of the square is `(4 * r^2)` unit sq, area of circle is `(π * r^2)`. The ratio of these two areas is `(π * r^2) / (4 * r^2) = π / 4`

Now for a very large number of generated points, `π / 4 = (number of points inside the circle) / (number of points inside the square)`.

## Used technologies:
- Python 3.11
- Jupyter notebook
- Matplotlib
- Numpy

## Learn more
- [Monte Carlo method](https://en.wikipedia.org/wiki/Monte_Carlo_method)
- [Matplotlib](https://matplotlib.org/)
