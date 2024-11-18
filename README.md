Berlin Traffic Data Clustering with K-Means

This project analyzes Berlin traffic data using the K-Means Clustering algorithm. By grouping data points into clusters based on traffic density and speed metrics, it provides insights into urban traffic patterns. The project includes data standardization, the elbow method to determine optimal clusters, and visualization of clustering results.
 
Table of Contents
1.	Project Overview
2.	Dataset
3.	Installation
4.	Usage
5.	Results
6.	Technologies Used
7.	License
 
Project Overview

Clustering traffic data helps identify patterns and trends in vehicle behavior, enabling better traffic management and urban planning. This project:
-	Utilizes K-Means Clustering to group traffic data into clusters.
-	Determines the optimal number of clusters using the Elbow Method.
-	Visualizes clustering results for better interpretability.
 
Dataset

The dataset includes the following features:
-	vehicle_count_per_hour: Total vehicles per hour.
-	avg_speed_all_vehicles_kmh: Average speed of all vehicles.
-	car_count_per_hour: Total cars per hour.
-	avg_speed_cars_kmh: Average speed of cars.
-	truck_count_per_hour: Total trucks per hour.
-	avg_speed_trucks_kmh: Average speed of trucks.
 
Installation
1.	Clone the repository:
git clone https://github.com/yourusername/Berlin-Traffic-KMeans.git
cd Berlin-Traffic-KMeans
2.	Set up a Python virtual environment (optional but recommended):
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
3.	Install the required dependencies:
pip install pandas matplotlib scikit-learn
 
Usage
1.	Load the Dataset: Ensure the dataset (berlin_traffic_data.csv) is in the project directory.
2.	Run the Script: Execute the script to cluster the data and generate visualizations:
python berlin_traffic_kmeans.py
3.	Outputs:
   -	Scatter Plot: Data before clustering.
   -	Elbow Method: Helps determine the optimal number of clusters.
   -	Clustered Data Visualization: Displays data points grouped into clusters.
 
Results
1.	Optimal Cluster Count: Determined using the Elbow Method, where WCSS (Within-Cluster Sum of Squares) is plotted for different cluster counts.
2.	Clustered Data: Data points are grouped into 3 clusters (or any chosen number of clusters), with each point labeled by its cluster.
3.	Visualizations:
   - Before Clustering: Shows the distribution of traffic speed vs. vehicle count.
   - Clustered Data: Highlights grouped data points with distinct colors for each cluster.
 
Technologies Used
-	Python: Programming language.
-	Pandas: For data manipulation.
-	scikit-learn: For scaling and K-Means clustering.
-	Matplotlib: For visualizations.
 
License
This project is licensed under the MIT License.
