# LGMVIP-DataScience-Task2
## Iris Flowers Classification ML

This project involves building a classification model using the famous Iris dataset from the UCI Machine Learning Repository. Here's a short description of what the code does:

1. **Data Loading and Exploration:**
   - Loads the Iris dataset from the UCI repository.
   - Prints the first few rows, statistical summary, and class distribution of the dataset.
   
2. **Data Visualization:**
   - Uses Seaborn to create a pair plot to visualize the relationships between different features (Sepal Length, Sepal Width, Petal Length, Petal Width) colored by species.

3. **Data Preparation:**
   - Splits the dataset into features (`X`) and target (`y`).
   - Splits the data into training and testing sets (80% training, 20% testing).
   - Standardizes the features using `StandardScaler` to normalize the feature values.

4. **Model Training:**
   - Trains a k-Nearest Neighbors (KNN) classifier with `n_neighbors=5` using the training data.

5. **Model Evaluation:**
   - Makes predictions on the test set.
   - Prints a confusion matrix, classification report (precision, recall, F1-score), and overall accuracy score of the model.

6. **Example Prediction:**
   - Provides an example prediction using a new set of feature values (`[5.1, 3.5, 1.4, 0.2]`), scaled using the same `StandardScaler` object.

This project demonstrates a typical machine learning workflow including data loading, exploration, visualization, preprocessing, model training, evaluation, and prediction. It's a good starting point for understanding classification tasks using machine learning algorithms like KNN.
