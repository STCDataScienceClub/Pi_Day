
# Happy π Day!!

---
## Estimate π Using Random Numbers

Thanks to this article by [Bence Komarniczky](https://towardsdatascience.com/estimate-pi-using-random-numbers-8b13a7e8c791) and the YouTube video by [Joma Tech](https://www.youtube.com/watch?v=pvimAM_SLic).

### Problem

If given a random number generator, can you estimate the value of π?

## Area of a Circle Formula

The formula for calculating the area (\(A\)) of a circle is given by:

 A = π  r**2

Where:
- A is the area of the circle,
- π is a mathematical constant approximately equal to 3.14159,
- r is the radius of the circle.

To find the area of a circle, square the radius and multiply the result by π.

### Example

Consider a circle with a radius of 1. To find its area, we'll graph random numbers between 0 and 1 and compare the count of numbers inside the circle to those outside. We can then solve for π.

To determine if a point is inside the circle, we need to check if it is farther than the radius from the center of the circle.

#### Area of Circle = π  r**2  (number of points inside the circle)
#### Area of Square =  (2 * r)**2  (total number of points)

#### Solve for π
Substitute r = 1:

 π * 1**2{(2 * 1)**2} = num_points_circle/num_points_total

 π * 1/4 = num_points_circle/num_points_total

Multiply each side by 4:

π = 4 * num_points_circle/num_points_total