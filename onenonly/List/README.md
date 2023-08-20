# ***`onenonly.List`*** is a python module
Aim for this module is to work with list that contains number and  perform some mathematics within the list such as

- element_wise_operation(*lists:list,operation)
- product/add/sub/div/floor-div b/w multiple list or with scalar
- modulo with multiple list and with scalar
- also flatten the list

# Example

```python
import onenonly.List as List

x = [1,2,3,4]
y = [5,6,7,8]

print(List.add(x,y)) # [6, 8, 10, 12]
print(List.scalarAdd(x,1)) # [2, 3, 4, 5]

print(List.sub(x,y)) # [-4, -4, -4, -4]
print(List.scalarSub(x,1)) # [0, 1, 2, 3]

print(List.product(x,y)) # [5, 12, 21, 32]
print(List.scalarProduct(x,2)) # [2, 4, 6, 8]
print(List.dotProduct(x,y)) # 70

print(List.div(x,y)) # [0.2, 0.3333333333333333, 0.42857142857142855, 0.5]
print(List.scalarDiv(x,2)) # [0.5, 1.0, 1.5, 2.0]

print(List.floorDiv(x,y)) # [0, 0, 0, 0]
print(List.scalarFloorDiv(x,2)) # [0, 1, 1, 2]

print(List.modulo(x,y)) # [1, 2, 3, 4]
print(List.scalarModulo(x,2)) # [1, 0, 1, 0]

print(List.flatten([[1,2,3],[2],1,2,4,[4,5,[2]]])) # [1, 2, 3, 2, 1, 2, 4, 4, 5, 2]
```
