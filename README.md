## Compute the times of elastic collisions between two objects and a wall

Object A stays between a wall and object B. Object B moves with velocity V to collide with object A. Count the times of collision between object A and B, and between object A and the wall. 

<!-- language: lang-none -->
    wall
    |
    |
    |    A    v   B
    |    o   <--  O


The mass of B is 100^n times of A's mass. Then the bounce times become Pi x 10^n.
<!-- language: lang-none -->
       n    bouncing-times
       0     3
       1     31
       2     314
       3     3141
       4     31415
       5     314159
       6     3141592
       7     31415926
       8     314159265
    
This can be proven in math.

One way to prove it is to treat the velocities (with direction) of Va and Vb as the cordinate (x, y) of a point on a circle, based on the law of kinect energy conservation in elastic collision. I will put here a solution when I can spare some time.
