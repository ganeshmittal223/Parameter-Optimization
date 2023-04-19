# Parameter-Optimization
## Objective
The objective of this project was to assess the effectiveness of Support Vector Machines (SVM) in solving classification problems by optimizing SVM parameters. We utilized the Scikit-learn library in Python to implement SVM models on the room occupancy Data Set, which was randomly split into 10 samples for training and testing. Through experimentation with various SVM parameter combinations, we identified the optimal settings for each sample. The resulting table displays the accuracy achieved for each sample, along with the corresponding SVM parameters that yielded the highest accuracy. This table can be utilized as a valuable reference for future classification tasks that require SVM parameter optimization.

## About Data-set
The "Room Occupancy Estimation Data Set" available on the UCI Machine Learning Repository comprises 20,560 instances and includes 7 features such as temperature, relative humidity, light intensity, CO2 level, humidity ratio, and binary occupancy labels. This dataset is commonly used for binary classification tasks focused on predicting room occupancy based on sensor measurements, making it relevant for research in areas such as energy management in buildings and smart homes. It serves as a valuable resource for evaluating and comparing the performance of different machine learning algorithms, including Support Vector Machines (SVM), in the context of estimating room occupancy.

## Result
### Table
Sample	Best Accuracy	Best Kernel	Best Nu	Best Epsilon
0	1	0.88	poly	2.64	9.95
1	2	0.95	linear	7.00	1.38
2	3	0.96	linear	9.11	9.44
3	4	0.94	poly	8.19	4.22
4	5	0.93	linear	1.69	9.72
5	6	0.84	poly	7.53	1.88
6	7	0.91	poly	4.38	7.09
7	8	0.96	poly	4.25	3.44
8	9	0.93	poly	3.99	4.74
9	10	0.95	poly	9.14	3.99

### Graph

![image](https://user-images.githubusercontent.com/78275410/233170607-95eceec9-d0b2-453a-bd78-c21767426477.png)

## Discussion
From the above graph, we can conclude that the model is well trained and parameter have been optimized due to the less gap between training and cross-validation curve.

The graph is made for the sample which has best accuracy. Sample 9 has the best accuracy of 0.97 having kernel = Poly, Nu = 1.27 and Epsilon = 6.87.
