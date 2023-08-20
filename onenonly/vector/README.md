# Vector
using this module you can work with vector calculations that consist

1. ***`Vector.toList(self)`*** convert the vector to list data type
2. ***`Vector.get(self,direction:int)`*** get the value of vector using direction(1-3)
3. ***`Vector.assign(self,direction:int,value:int|float)`*** set the value of vector using direction(1-3) and set the value via value
4. ***`Vector.dot(self,other)`*** dot product between two vectors
5. ***`Vector.cross(self,other)`*** corss product between two vectors
6. ***`Vector.magnitude(self)`*** find the magnitude of the vector
7. ***`Vector.projection(self,other)`*** find the projection of the vector a to b vector
8. ***`Vector.add(self,other)`*** add two vectors or a scalar to vector
9. ***`Vector.sub(self,other)`*** subtract two vectors or a scalar from vector
10. ***`Vector.prod(self,scalar=1.0)`*** simple product between scalar and vector
11. ***`Vector.div(self,scalar=1.0)`*** simple division between scalar
13. ***`Vector.floor_div(self,scalar=1.0)`*** simple floor division between scalar
14. ***`Vector.octant(self)`*** find the octanct of the vector

```python
from onenonly.vector import Vector

vec1 = Vector([1,2,3])
vec2 = Vector([1,4,9])
vec3 = Vector([-1,4,-10])

# add two vector as well as vector with scalar
print(vec1.add(vec2)) # <2 6 12>
print(vec1.add(2)) # <3 4 5>

# subtract two vector as well as vector with scalar
print(vec1.sub(vec2)) # <0 -2 -6>
print(vec1.sub(2)) # <-1 0 1>

# dot product
print(vec1.dot(vec2)) # 36

# cross product
print(vec1.cross(vec2)) # <6 -6 2>

# magnitude
print(vec1.magnitude()) # 3.74165738

# projection
print(vec1.projection(vec2)) # <0.36734693 1.46938775 3.30612244>

# power
print(vec1.pow(2)) # <1 4 9>

# product
print(vec1.prod(3)) # <3 6 9>

# div
print(vec1.div(2)) # <0.5 1.0 1.5>

# floor div
print(vec1.floor_div(2)) # <0 1 1>

# octant
print(vec1.octant()) # 1
print(vec3.octant()) # 6

# from vector to list
print(vec1.toList()) # [1, 2, 3]

# get
print(vec1.get(2)) # 2
print(vec1.i,vec1.j,vec1.k) # 1 2 3

# assign
print(vec1.assign(1,3)) # <3 2 3>
vec1.i = 1
vec1.j = 10
vec1.k = 100
print(vec1) # <1 10 100>
```
