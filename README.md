# Vector GeoData & K-Means clustering
In this repository, I performed 3 tasks in total. (1) Math computation for geometries, (2) GeoData operation, (3) K-means clustering.
GeoData (geographic data) will be applied in my project, so the coordinates will be defined by latitudes and longitudes, which refer to y-coordinates and x-coordinates respectively in Cassette coordinates.

## Task 1: Math computation for geometries
<p>
  In this task, I performed general mathematical computation to calculate/determine the centroid of a polygon.
  The procedure contains 3 steps:<br>
  Step 1. Set up classes of Point, Polyline, and Polygon.<br>
  Step 2. Set up functions (methods) in each class.<br>
  Step 3. Demonstrate the functionality of these class at the end<br>
</p>
<p>
  The method in Polyline class allows users to calcuate the length
  The method in the Polygon class allows users to <br>
  (1) calculate the area<br> 
  (2) get the coordinate of the centroid of a polygon <br>
  (3) determine 4 boundaries of the minimum envelope which may be referred to as Bounding Box.
 </p>

## Task 2: Geometry Operation and Geodata Structure
<p>
  In this task, I'll use pandas, Geopandas, json, and numpy libraries for reading and loading the data retrieved from Flickr. Using shapely along with pylab to visualize the location of data, then creating a convex hull for the data in a city. The purpose of convex hull is used to visualize the minimum geographic extent of a cluster. In this task, the data is classified by its location, which is the city they belong to, instead of applying the clustering algorithm to classify them.
</p>

## Task 3: Customized K-means clustering
<p>
  In this task, I'll manually create a K-means clustering function. Different from the existing K-means you can get in other libraries, my K-means uses GeoDataFrame as the input. It would make geodata users process the data easier, it also demonstrates my ability to create and customize the functions as needed.
</p>

## Task 4: Clustering in scikit-learn
<p>
  This task demonstrated the ability to use the machine learning kit to perform different clustering methods. You could also compare the K-means result in Sciki-learn with my K-means method in the previous task to check whether they have nearly the same functionality. Other than these, I also compare the result of DBSCAN with K-means to determine which one is the better way to classify the data in my case.
