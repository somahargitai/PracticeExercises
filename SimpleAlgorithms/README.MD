# Simple Algorithms
These exercises can be solved in any popular, general purpose programming language.

### Shape detection
Given a 2D array, containing 1 and 0 values. Write function to detect if they form a rectangle shape, a triangle shape or none.

example data:
```
0 0 0 0 0   |   1 0 0 0 0   
0 1 1 1 1   |   1 1 0 0 0   
0 1 0 0 1   |   1 0 1 0 0   
0 1 1 1 1   |   1 1 1 1 0   
0 0 0 0 0   |   0 0 0 0 0   
```


Hint:
- Angles of triangles can be 90-45-45 only
- their orientation can be different
- 2D array are not necessarily 5x5 squares

Advanced:
- detect rectangles which are not parallel to array edges
- detect triangles which have only one edge parallel to array edges
- detect squares