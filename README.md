# DBSCAN_Clustering
DBSCAN stands for Density-Based Spatial Clustering Of Applications With Noise. This algorithm creates clusters based on the density of points int the neighborhood of a given point.
<br>
<br>
This algorithm takes two hyperparameters, epsilon(eps) and minPts(min points). 
<br>
<h5>Epsilon (eps)</h5>- It is the radius of the hypersphere neighborhood around a point. All points inside this radius neighbors.
<br>
<h5>Min Points (minPts)</h5>- It is the minimum number of neighbor points to be inside the hypersphere for the other point to be considered a core point.
<br>
<br>
This algorithm classifies a point into 3 types: core point, border point and noise. 
<br>
<h5>Core point</h5>- A point, which has neighbor points >= minPts inside its hypershere is called a core point.
<br>
<h5>Border point</h5>- A point which is not a core point but is neighbor of a core point is a border point.
<br>
<h5>Noise</h5>- A point which is neither a core point nor a border point is called noise.
<br>
![Point](https://github.com/user-attachments/assets/0bd425bf-e1fc-42ea-a675-077718fc5fff)


