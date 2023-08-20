# Mathematical Shapes Library (onenonly.areas)
The Mathematical Shapes Library (onenonly.areas) is a Python library that provides functions to calculate the areas of various geometric shapes. This library is designed to make it easy for developers and students to compute the area of shapes commonly encountered in geometry. Whether you're a student exploring mathematics or a developer working on a project that involves geometric calculations, this library can be a valuable addition to your toolkit.

## Installation
You can install the onenonly library using pip:

```bash
pip install onenonly
```
## Usage
Once you've installed the library, you can import it and use its functions to calculate the areas of different shapes.

```python
import onenonly.areas as areas
import onenonly.maths as maths
import onenonly.const as const

## Calculate the area of a square
side = 5
square_area = areas.square(side)
print(f"The area of the square with side {side} is: {square_area}")

# Calculate the area of a rectangle
length = 8
breadth = 6
rectangle_area = areas.rectangle(length, breadth)
print(f"The area of the rectangle with length {length} and breadth {breadth} is: {rectangle_area}")

# Calculate the area of an equilateral triangle
triangle_length = 7
equi_triangle_area = areas.equiTriangle(triangle_length)
print(f"The area of the equilateral triangle with side {triangle_length} is: {equi_triangle_area}")

# Calculate the area of an isosceles triangle
a = 5
b = 4
iso_triangle_area = areas.isoTriangle(a, b)
print(f"The area of the isosceles triangle with sides {a} and {b} is: {iso_triangle_area}")

# Calculate the area of a circle
radius = 10
circle_area = areas.circle(radius)
print(f"The area of the circle with radius {radius} is: {circle_area}")

# Calculate the area of a semicircle
semi_circle_area = areas.semiCircle(radius)
print(f"The area of the semicircle with radius {radius} is: {semi_circle_area}")

# Calculate the area of a quarter circle
quarter_circle_area = areas.quarterCircle(radius)
print(f"The area of the quarter circle with radius {radius} is: {quarter_circle_area}")

# Calculate the area of a sector
angle = 60  # in degrees
sector_area_deg = areas.sector(radius, angle, unit="deg")
print(f"The area of the sector with radius {radius} and angle {angle} degrees is: {sector_area_deg}")

# Calculate the area of a sector using radians
angle_rad = maths.deg2rad(45)  # convert to radians
sector_area_rad = areas.sector(radius, angle_rad, unit="rad")
print(f"The area of the sector with radius {radius} and angle {angle_rad} radians is: {sector_area_rad}")
```

## Documentation
For detailed information about each function and its parameters, you can refer to the official documentation.
