# Silicon-Wafer-Fault-Detector-in-Semiconductor-Manufacturing
Trained a machine learning model to correct any raw equipment faults that cause to get errors in the fabrication process.
# Aim-
To train a machine learning model to correct any raw equipment faults that cause to get error in fabrication process.
# Methodology-
Firstly, importing the dataset in our Python code and removed unwanted features which are of no use. Some features are highly correlated like more than 90% and were removed. Replaced null values with standard techniques in ML in our dataset.
Then model is trained for the dataset which applies Logistic Regression, SVM, Decision Tree, Random Forest and KNN.
#Results-
Model Training through Logistic Regression:
Accuracy of Training-0.9829787234042553
Accuracy of Testing-0.8852040816326531
Model Training through SVM:
Accuracy of Training-0.9421276595744681
Accuracy of Testing-0.9336734693877551
Model Training through Decision Tree:
Accuracy of Training-1.0
Accuracy of Testing-0.8724489795918368
Model Training through KNN:
Accuracy of Training-0.9361702127659575
Accuracy of Testing-0.9336734693877551
From the chart we can conclude SVM model is the best for the training getting the less difference in the accuracy of training and testing.
As the training and testing both are very close to each set and at high rate.
We have tried for No underfitting and overfitting because model with high and low accuracy is training and testing were neglected.
So lastly, I want to conclude that in this training model it accurately predict the equipment faults during the wafer fabrication process of the semiconductor industry.
