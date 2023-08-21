# Vector
using this module you can work with vector calculations that consist

1. ***`Vector.toList(self)`*** convert the vector to list data type
2. ***`Vector.get(self,direction:int)`*** get the value of vector using direction(1-3)
3. ***`Vector.assign(self,direction:int,value:int|float)`*** set the value of vector using direction(1-3) and set the value via value
4. ***`Vector.dot(self,other)`*** dot product between two vectors
5. ***`Vector.cross(self,other)`*** corss product between two vectors
6. ***`Vector.magnitude(self)`*** find the magnitude of the vector
7. ***`Vector.projection(self,other)`*** find the projection of the vector a to b vector
8. ***`Vector.angle(self,other)`*** find the angle between two vectors
9. ***`Vector.distance(self,other)`*** find the distance two vectors
10. ***`Vector.unitVector(self)`*** find the unit vector
11. ***`Vector.orthogonalTo(self,other)`*** check if two vectors are in perpendicular to each other or not
12. ***`Vector.parallelTo(self,other)`*** check if two vectors are in parallel to each other or not
13. ***`Vector.compareWith(self,other)`*** check for the first vector if its greater than other or not
14. ***`Vector.scalarProjection(self,other)`*** find the scalar projection of the vector a to b vector
15. ***`Vector.add(self,other)`*** add two vectors or a scalar to vector
16. ***`Vector.sub(self,other)`*** subtract two vectors or a scalar from vector
17. ***`Vector.prod(self,scalar=1.0)`*** simple product between scalar and vector
18. ***`Vector.div(self,scalar=1.0)`*** simple division between scalar
19. ***`Vector.floor_div(self,scalar=1.0)`*** simple floor division between scalar
20. ***`Vector.octant(self)`*** find the octanct of the vector

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
print(vec1.scalarProjection(vec2)) # 0.36734693876760555

# angle between two vectors
print(vec1.angle(vec2)) # 13.612751361088442

# distance between two vectors
print(vec1.distance(vec2)) # 6.324555337642616

# unit vector
print(vec1.unitVector()) # <0.26726124191242406 0.5345224838248481 0.8017837257372722>
print(vec2.unitVector()) # <0.10101525445413423 0.4040610178165369 0.9091372900872081>

# orthogonal vector
print(vec1.orthogonalTo(vec2)) # False

# parallel vector
print(vec1.parallelTo(vec2)) # False

# comparing vectors
print(vec1.compareWith(vec2)) # -1

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
