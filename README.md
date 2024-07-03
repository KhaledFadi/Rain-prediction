# Weather Data Classification Project
## Overview
This project involves analyzing and classifying weather data using various machine learning algorithms. The project includes data cleaning, preprocessing, visualization, and model training to predict weather-related attributes.

## Table of Contents
* Installation
* Data Description
* Data Cleaning
* Data Preprocessing
* Data Visualization
* Model Training and Evaluation
* Results
* Contributing
* License
## Installation
To run this project, you need to have Python and the following libraries installed:

* pandas
* numpy
* matplotlib
* scikit-learn
## Data Description
The dataset used in this project is a CSV file containing weather data. The dataset includes features such as temperature, humidity, pressure, visibility, wind speed, and a target variable indicating the precipitation type.

## Data Cleaning
Handling Missing Values: Removing rows with null values.
Duplicate Records: Identifying and removing duplicate records.
## Data Preprocessing
1-Viewing Data: Displaying the first and last 10 rows of the dataset.

2-Descriptive Statistics: Calculating statistical measures for the dataset.

3-Grouping and Filtering: Grouping data by visibility and calculating mean temperature, filtering data based on visibility, and more.

4-Scaling: Normalizing the feature columns using MinMaxScaler.
## Data Visualization
1-Histograms: Plotting histograms to show the distribution of temperature.

2-Scatter Plots: Visualizing the relationship between humidity and temperature.
## Model Training and Evaluation
The following machine learning models are trained and evaluated:

1-K-Nearest Neighbors (KNN):

* Defining the model and training on the dataset.
* Evaluating the model using accuracy score and confusion matrix.

2-Naive Bayes:

* Defining the Gaussian Naive Bayes model.
* Training and evaluating the model using accuracy score and confusion matrix.
  
3-Support Vector Machine (SVM):

* Defining the SVM model with linear kernel.
* Training and evaluating the model using accuracy score and confusion matrix.
## Results
The results of the models' performance are compared, and the accuracy of each model is reported. The confusion matrix is used to visualize the classification results.
## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License
This project is licensed under the MIT License.
