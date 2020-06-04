I have solved a 2D version of the problem which is extendable to 3D.

1. Any surface (in 3D) and edge (in 2D) can be possibly illuminated by a ray of sunlight iff 
   the angle between the sun-ray vector and the outward-normal from the surface/edge is obtuse.
2. Any possibly-illuminable edge/surface will have a shadow cast on it iff the outward plane/parallelopiped 
   towards the direction of the source of light is obstructed by another possibly-illuminable edge/surface.
3. Therefore for each illuminable edge, a polygon was constructed with parallel rays extending towards the light
   source from the end points of the edge. If any other illuminable edge lies partially or completely within this
   polygon then it casts a shadow on the initial edge.
4. The shadows of all such illuminable edges on a given illubinable edge have been calculated.
