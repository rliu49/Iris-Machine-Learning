# Iris-Machine-Learning

The Iris flower data set or Fisher's Iris data set is a multivariate data set introduced by the British statistician and biologist Ronald Fisher in his 1936 paper The use of multiple measurements in taxonomic problems as an example of linear discriminant analysis. The dataset contains 150 observations of iris flowers. There are four columns of measurements of the flowers in centimeters. The fifth column is the species of the flower observed. All observed flowers belong to one of three species.

<img src="https://github.com/rliu49/Iris-Machine-Learning/blob/master/Imgs/framework.png" height="400" width="900">

## Data Description 

Dimensions of the dataset.
Statistical summary of all attributes.
Breakdown of the data by the class variable.

<img src="https://github.com/rliu49/Iris-Machine-Learning/blob/master/Imgs/datades.png" height="900" width="600">

## Data Visualization
Create Univariate plots to better understand each attribute.
Multivariate plots to better understand the relationships between attributes.
Box and Whisker Plot:

<img src="https://github.com/rliu49/Iris-Machine-Learning/blob/master/Imgs/box%20and%20whisker%20plots.png" height="400" width="500">

Histogram :

<img src="https://github.com/rliu49/Iris-Machine-Learning/blob/master/Imgs/histogram.png" height="400" width="500">

Scatter Plot Matrix:
Multivariate plots to better understand the relationships between attributes.The suggests a high correlation and a predictable relationship.

<img src="https://github.com/rliu49/Iris-Machine-Learning/blob/master/Imgs/scatter%20plot%20matrix.png" height="400" width="500">

## Evaluate Algorithms

1, Separate out a validation dataset:We will split the loaded dataset into two, 80% of which we will use to train our models and 20% that we will hold back as a validation dataset.

2, Set-up the test harness to use 10-fold cross validation:We will use 10-fold cross validation to estimate accuracy.
This will split our dataset into 10 parts, train on 9 and test on 1 and repeat for all combinations of train-test splits.
Using the metric of ‘accuracy‘ to evaluate models. This is a ratio of the number of correctly predicted instances in divided by the total number of instances in the dataset multiplied by 100 to give a percentage (e.g. 95% accurate).

3, Build 5 different models to predict species from flower measurements:
Logistic Regression (LR)
Linear Discriminant Analysis (LDA)
K-Nearest Neighbors (KNN).
Classification and Regression Trees (CART).
Gaussian Naive Bayes (NB).
Support Vector Machines (SVM).

4, Select the best model based on accuracy score.

<img src="https://github.com/rliu49/Iris-Machine-Learning/blob/master/Imgs/comparison.png" height="400" width="500">

## Prediction & Accuracy Score
The KNN algorithm was the most accurate model. The accuracy is 0.9 or 90%. The confusion matrix provides an indication of the three errors made.
<img src="https://github.com/rliu49/Iris-Machine-Learning/blob/master/Imgs/predication.png" height="350" width="850">
