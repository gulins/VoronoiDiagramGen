# Optimal Transport Project
Code snippets used in generating diagrams for my maths master's project.

## voronoi/voronoigen.m
Voronoi Diagram generator with variable number of sites, weights of each site and location of each site. By changing the distance function, one can create different partitionings of the plane. For example, a typical Voronoi diagram with Euclidean distance is

![Euclidean distance](voronoi/p2.png)

If we use the taxicab metric (L<sub>1</sub> distance), the Voronoi diagram looks like the following

![L1 distance](voronoi/taxicab.png)

