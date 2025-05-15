# Stats&ML

---

## Day 1 
**Exploratory Data Analysis on a Real-World Dataset:** I wanted to enhance my data analysis skills by working with a real-world dataset, performing statistical analysis, and visualizing key insights. 
**Steps:** 
 - Loaded a benchmark dataset from a real-world source. 
 - Conducted descriptive statistical analysis, including measures of central tendency and dispersion.
 - Created meaningful visualizations to uncover patterns and trends in the dataset.

---

## Day 2 
**Understanding Sampling Techniques and the Central Limit Theorem:** I was curious about how different sampling methods impact statistical analysis and wanted to explore the Central Limit Theorem in action.
Dataset: Used the Iris dataset to apply different sampling techniques. 
**Steps:** 
 - Loaded the dataset and explored its structure. 
 - Performed simple random sampling by selecting 30 observations. 
 - Repeated sampling 100 times, calculated sample means, and plotted the distribution to visualize the Central Limit Theorem. 
 - Implemented systematic sampling by selecting 20% of the dataset with a custom function and compared it with the original dataset.

---

## Day 3 
**Statistical Hypothesis Testing on the Iris Dataset:** I wanted to deepen my understanding of hypothesis testing by applying statistical tests to compare different species in the Iris dataset. 
**Steps:** 
 - T-Test: Compared the mean petal lengths of Setosa and Versicolor to determine if they differ significantly. 
 - Z-Test: Tested whether the mean sepal length of a species equals a predefined value (5.0). 
 - ANOVA: Compared mean petal widths across all three species to check for significant differences.
 - Correlation & Regression: Explored the relationship between sepal length and petal length using statistical techniques.

---

## Day 4 
**Finding and Exploring a New Dataset for Analysis:** I wanted to practice dataset selection and exploratory analysis by working with a dataset of my choice. 
**Steps:** 
 - Researched and selected a dataset with at least 1,000 rows. 
 - Examined its structure, features, and relevance. 
 - Documented insights on why I chose the dataset and how it helps in learning data analysis concepts.

---

## Day 5
**Data Preprocessing and Feature Selection:** Data preprocessing is crucial for building effective machine learning models. I practiced handling missing values, scaling, outlier detection, and feature selection techniques. 
**Steps:**
 - Handling Missing Values: Identified and imputed missing data using appropriate techniques (mean, median, mode, or predictive modeling).
 - Scaling Data: Applied Z-score standardization and Min-Max normalization to numerical features. 
 - Handling Noise: Introduced random noise to a numerical feature and tested smoothing techniques to mitigate its effects. 
 - Outlier Detection & Handling: Used Z-score to detect outliers and applied removal or transformation techniques.
 - Feature Selection: Implemented and compared different feature selection methods: 
   ‣Filter Methods: Used correlation and mutual information to rank features. 
   ‣Wrapper Methods: Applied Recursive Feature Elimination (RFE) to optimize feature selection. 
   ‣Embedded Methods: Used Lasso regression for feature importance ranking.

---

## Day 6
# 1: Handwritten Digit Classification using a Feedforward Neural Network (FNN) Objective: Develop a deep learning model to classify handwritten digits (0-9) using the MNIST dataset. 
**Dataset:**
 - The MNIST dataset consists of 60,000 training images and 10,000 test images, each representing a 28x28 grayscale handwritten digit.
 - Labels range from 0 to 9, corresponding to the digit in the image.

# Approach: 
A feedforward neural network (FNN) is implemented using TensorFlow/Keras.
The model architecture: 
   - Flatten layer: Converts 28x28 images into a 1D array.
   - Hidden layer: 128 neurons with ReLU activation. 
   - Output layer: 10 neurons with Softmax activation for multi-class classification. 
   - The model is trained using Adam optimizer and Sparse Categorical Crossentropy loss.

# Evaluation:
 - The model achieves 98% accuracy on the test dataset.
 - Classification metrics (precision, recall, F1-score) show strong performance across all digit classes.

# 2: Predicting a Continuous Target Using a Regression Neural Network Objective: Build a neural network to predict a continuous target variable based on input features.
**Dataset:**
A synthetic dataset is generated, where: 
    - Input (X) consists of 1000 samples, each with 5 features.  
    - The target (Y) is the sum of the feature values with added noise.

# Approach:
A feedforward neural network (FNN) is implemented for regression: 
   - Input layer: 5 features. 
   - Hidden layers: 64 neurons (ReLU) → 32 neurons (ReLU). 
   - Output layer: 1 neuron (Linear activation) for regression output. 
   - Model trained using Adam optimizer and Mean Squared Error (MSE) loss.

# Evaluation: 
The model achieves a Root Mean Squared Error (RMSE) of ~0.14, indicating a good fit to the data.
