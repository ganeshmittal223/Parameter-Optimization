# Parameter-Optimization
## Objective
The objective of this project was to assess the effectiveness of Support Vector Machines (SVM) in solving classification problems by optimizing SVM parameters. We utilized the Scikit-learn library in Python to implement SVM models on the room occupancy Data Set, which was randomly split into 10 samples for training and testing. Through experimentation with various SVM parameter combinations, we identified the optimal settings for each sample. The resulting table displays the accuracy achieved for each sample, along with the corresponding SVM parameters that yielded the highest accuracy. This table can be utilized as a valuable reference for future classification tasks that require SVM parameter optimization.

## About Data-set
The "Room Occupancy Estimation Data Set" available on the UCI Machine Learning Repository ([https://archive.ics.uci.edu/ml/datasets/Room+Occupancy+Estimation](https://archive.ics.uci.edu/ml/datasets/Room+Occupancy+Estimation)
) comprises 20,560 instances and includes 7 features such as temperature, relative humidity, light intensity, CO2 level, humidity ratio, and binary occupancy labels. This dataset is commonly used for binary classification tasks focused on predicting room occupancy based on sensor measurements, making it relevant for research in areas such as energy management in buildings and smart homes. It serves as a valuable resource for evaluating and comparing the performance of different machine learning algorithms, including Support Vector Machines (SVM), in the context of estimating room occupancy.

## Result
### Table
![image](https://user-images.githubusercontent.com/78275410/233172460-02d47115-3b22-43ed-9744-eaded879254c.png)


### Graph

![image](https://user-images.githubusercontent.com/78275410/233170607-95eceec9-d0b2-453a-bd78-c21767426477.png)

## Discussion
From the above graph, we can conclude that the model is well trained and parameter have been optimized due to the less gap between training and cross-validation curve.

The graph is made for the sample which has best accuracy. Sample 7 has the best accuracy of 0.96 having kernel = Poly, Nu = 4.25 and Epsilon = 3.44.
