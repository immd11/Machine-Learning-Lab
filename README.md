# Machine-Learning-Lab
## K-Nearest Neighbors (KNN) Project

In this lab, we explored the K-Nearest Neighbors (KNN) classification algorithm using a synthetic dataset. The project focused on data preprocessing, model training, evaluation, and selecting the best K value for prediction accuracy.

We started by loading and visualizing the dataset using Seaborn pairplots to observe the relationship between features and target classes. Since KNN is sensitive to feature scales, we standardized the data using StandardScaler before splitting it into training and testing sets.

After training the KNN model, we evaluated its performance using a confusion matrix and classification report. We then applied the elbow method by testing multiple K values and tracking error rates to identify the optimal number of neighbors. Finally, the model was retrained using the best K value to improve classification performance.
