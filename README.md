# Week-Eight-Lab-Repository
This is repository dedicated to storing code that has been taken from lab eight, which can be meant for future reference

## Lab 8: KNN_sklearn
In this lab, you will experiment with using the sklearn library for KNN.

## Part 1 of Exercises
- [x] Use matplot lib to plot the groups of the X values coloring the points according to their labels ( y ). Then add two lines to the plot that
  show your approximation of where linear decision boundaries might lie to optimally separate the classes.

- [x] Experiment in the next cell with adjusting the variance when building additional random datasets. Write a few statements in your
  reflection below about how the variance affected the accuracy and whether overfitting occurred.

- [x] Read through the website: https://www.kaggle.com/fedesoriano/stroke-prediction-dataset where the following dataset was obtained.
  Create a feature description below.

- [x] Extract the age and hypertension columns as input features and stroke as output labels from the dataframe. Scale and split the data and
  then run the knn training and evaluation.

- [x] There are a few things going on here. First, we have a significant class imbalance problem. Write a 1-liner to calculate the ratio of stroke
  to non stroke patients in the dataset.

- [x] Figure out which class has fewer and how many samples exist for that class. Use the `sample()` method to undersample the data:
  https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.sample.html Join the results back into a single dataframe that
  represents the undersampled data (appropriately named).

## Part 2 of Exercises
- [x] Next, re-run the kNN training and determine the updated accuracy and confusion matrix. Write a few statements below for your reflection
  on the results. Make sure you answer the question, did overfitting occur?

- [x] Next, you should oversample the data and store the results in an appropriately-named dataframe. Again, you should use `sample()`.

- [x] Next, re-run the kNN training and determine the updated accuracy and confusion matrix. Write a few statements below for your reflection
  on the results. Make sure you answer the question, did overfitting occur?

- [x] Next, you should try at least two other combinations of features to see what affects they have on accuracy. At least one of your
  experiments should include categorical variables that have been converted to numerical. You should also experiment with at least 2
  additional values of k. In total, you should run at least 5 experiments, and you should document the results in a table below in the
  reflection section.

- [x] Next, you should experiment with a couple of different distance metrics. To change the metric, you should add a parameter (with an
  appropriate default) to the run_knn function and use the parameter to set the metric like this: KNeighborsClassifier(n_neighbors=2, metric=metric). Try at least 3 different metrics with the "best" accuracy configuration. Document the results in a table in the reflection section below.
  Please also record any observations about using different metrics