Customer Churn Prediction
This repository focuses on predicting customer churn in a company using various machine learning techniques. The dataset includes features related to customer demographics, behaviors, and engagement metrics, which are critical for understanding why customers may choose to leave.

Tasks
Data Cleaning and Processing:

Load the dataset using Pandas and check for duplicated and missing values.
Address anomalies, such as '?' representing missing values, and optimize data types to improve memory efficiency.
Normalize and visualize the data to gain insights into relationships between features using heatmaps.
Machine Learning Model Training:

Implement various classification algorithms to evaluate their performance.
Start with K-Nearest Neighbors (KNN), achieving high accuracy through cross-validation.
Next, utilize a Decision Tree classifier and enhance its performance with AdaBoost.
Finally, apply Gradient Boosting to the dataset, identifying it as the most efficient model with an accuracy of 87%.
Neural Network Construction:

Design and train a neural network, experimenting with different architectures, including the number of layers and neurons.
Optimize the model using parameters such as the number of epochs, batch sizes, and activation functions.
The neural network achieves a test accuracy of 86.43%, demonstrating its effectiveness in predicting customer churn.
Comparison of Models:

Compare the performance of the best classical machine learning model (Gradient Boosting) and the neural network, highlighting the strengths and weaknesses of each approach.
Conclusion
This project aims to provide a comprehensive understanding of customer churn prediction and the effectiveness of various machine learning methodologies, offering valuable insights for businesses looking to retain their customers.
