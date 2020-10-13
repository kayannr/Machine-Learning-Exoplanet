# Machine Learning Homework - Exoplanet Exploration
![exoplanets.jpg](images/exoplanets.jpg)

## Background

Over a period of nine years in deep space, the NASA Kepler space telescope has been out on a planet-hunting mission to discover hidden planets outside of our solar system.
To help process this data, machine learning models capable of classifying candidate exoplanets from the raw dataset are created. The following tasks are completed: 

1. [Preprocess the raw data](#Preprocessing)
* Preprocess the dataset prior to fitting the model.
* Perform feature selection and remove unnecessary features.
* Use `MinMaxScaler` to scale the numerical data.
* Separate the data into training and testing data.
2. [Tune the models](#Tune-Model-Parameters)
* Use `GridSearch` to tune model parameters.
* Tune and compare at least two different classifiers.
3. [Compare two or more models](#Evaluate-Model-Performance)
* Deep Learning
>   * Normal Neural Network - Loss: 0.27885300943998775, Accuracy: 0.8872997714398382
* Support-Vector Machine (SVM)
>   * Training Data Score: 0.8439824527942018
>   * Testing Data Score: 0.8415331807780321
* Logistic Regression

>   * Training Data Score: 0.663932862864772
>   * Testing Data Score: 0.6693363844393593

This model results in a lowe accuracy score compare to the other two models used above. The possible reason for low accuracy on a classification could mean that classes are not very well separable with the current features chosen. This can possibly be improved by using better features. 



