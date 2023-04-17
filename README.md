# Vector GeoData & K Means clustering
In this repository, I performed 3 tasks in total. (1) Math computation for geometries, (2) GeoData operation, (3) K-means clustering.
GeoData (geographic data) will be applied in my project, so the coordinates will be defined by latitudes and longitudes, which refer to y-coordinates and x-coordinates respectively in Cassette coordinates.

## Task 1: Math computation for geometries
In this section, I performed general mathematical computation to calculate/determine the centroid of a polygon.
The procedure contains 3 steps:
Step 1. Set up classes of Point, Polyline, and Polygon.
Step 2. Set up functions (methods) in each class.
Step 3. Demonstrate the functionality of these class at the end

The method in Polyline class allows users to calcuate the length
The method in the Polygon class allows users to (1) calculate the area, (2) get the coordinate of the centroid of a polygon (3) determine 4 boundaries of the minimum envelope which may be referred to as Bounding Box.
