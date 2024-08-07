# MT-CEA 
The **MT-CEA(Mixed Temporal Cluster Evolution Analysis)** is a framework proposed in a research article named "MT-CEA Framework for Dynamic Clustering of Students’
Performance Trajectories on University Courses" by Authors Muhammad Hannan Farooq, Rabia Maqsood, Paolo Ceravolo and Crist¢bal Romero .

This framework performs dynamic clustering of the input mixed type data temporally using the K-prototype clustering algorithm. That is, students' transcript data of each specific semester was grouped into K number of clusters where the number of clusters and their characteristics may vary between the two subsequent semesters (or time-spans), which is the underlying idea of dynamic clustering. The transcript records were grouped into 331 clusters for over 12 semesters (or timestamps).

In the MT-CEA framework, we devised a data-independent approach to calculate between-cluster similarity for mixed data using centroid feature vectors. This resulted in 116 new and 215 repeating states where each unique state was given a label based on the cluster's characteristics. Finally, as an outcome. We also proposed a **custom line charts** (Min-Max, Median, and Pair-Pair). The code is available in custom-line-charts folder developed in python.

The **dynamic clusters** as a result of MT-CEA are also available in folder dynamic-cluster-donut-charts.
