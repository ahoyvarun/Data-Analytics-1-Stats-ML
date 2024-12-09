# Data-Analytics-1-Stats-ML
Questions:

Day1: 
Real-World Data Analysis:
  ‣Read data from a CSV dataset (use a real-world benchmark dataset).
  ‣Perform descriptive statistical analysis on the dataset, including measures of central tendency and dispersion.
  ‣Plot meaningful and significant visualizations to illustrate key insights from the data.

Day2:
Central Limit Theorem and Sampling Methods
Objective:
Use the Central Limit Theorem to analyze sample means and apply basic sampling methods to a real-world dataset.
Dataset:
Use the "Iris" dataset, widely available in data science resources and Python libraries.
Tasks:
1. Data Loading and Overview:
   ‣Load the Iris dataset using Python's seaborn or sklearn library.
   ‣Display the first few rows to get familiar with the data.
2. Simple Random Sampling:
   ‣Randomly sample 30 observations from the dataset.
3. Sample Mean Distribution Analysis:
   ‣Repeat the random sampling 100 times, each time calculating the mean sepal length.
   ‣Plot the distribution of these 100 sample means using a histogram.
4. Do sampling like systematic sampling by taking 20percent of dataset with your novel function and
then plot original and sample datset.

Day3:
Use the Iris dataset from Day 3 or a sampled subset.
1. T-Test:
   ‣Compare the mean petal lengths of two species (e.g., Setosa vs. Versicolor).
   ‣Null Hypothesis: Means are equal.
   ‣Use an independent t-test.
2. Z-Test:
   ‣Test if the mean sepal length of one species equals a specific value (e.g., 5.0).
   ‣Null Hypothesis: Mean equals 5.0.
   ‣Perform only if population standard deviation is known or n>30n > 30n>30.
3. ANOVA:
   ‣Compare mean petal widths across all three species.
   ‣Null Hypothesis: All means are equal.
4. Correlation/Regression:
   ‣Explore the relationship between sepal length and petal length.

Day4:
1. Find a Dataset to Work With
   ‣Search for a dataset that interests you.
   ‣The dataset should have at least 1,000 rows of data.
2. Explain the Dataset
   ‣What is the dataset about?
   ‣Why did you choose this dataset?
   ‣How will it help you in learning the concepts covered in this chapter?

Day5:
Using a dataset containing both numerical and categorical features, perform the following tasks:
1. Handling Missing Values:
   ‣Identify and impute missing values using appropriate methods (e.g., mean, median, mode, or predictive modeling.)
2. Scaling Data:
   ‣Scale numerical features using standardization (Z-score) and normalization (Min-Max scaling).
3. Handling Noise:
   ‣Inject random noise into one of the numerical features and apply techniques to smooth or remove the noise.
4. Handling Outliers:
   ‣Detect outliers using methods like Z-score.
   ‣Handle them through removal or transformation.
5. Feature Selection: Implement and compare the following feature selection methods.
   ‣Filter Methods (e.g., correlation, mutual information).
   ‣Wrapper Methods (e.g., Recursive Feature Elimination, Backward).
   ‣Embedded Methods (e.g., Lasso regression).

