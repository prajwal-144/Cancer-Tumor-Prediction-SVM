# Cancer-Tumor-Prediction-SVM
SVM Model for predicting if the tumor is Malignant or Benign

# SVM
Support Vector Machine is a supervised learning algorithm used mostly for classification in Machine Learning and Deep Learning. It looks at extremes of the dataset and draws a hypothetical decision boundary known as Hyperplane to segregate different classes. These extreme cases are called support vectors.

<p align="center">
![support-vector-machine-algorithm](https://user-images.githubusercontent.com/86421205/146558111-55ca5980-2f4e-45e1-a1ee-977e8dace5df.png)
</p>

If the number of input features is two, then the hyperplane is a line. If the number of input features is three, then the hyperplane becomes a 2-D plane.

# Code
This model focuses on Cancer/Tumor type prediction. The result to be predicted is either Benign or Malignant.

The dataset has the following features:

'Clump', 'UnifSize','UnifShape','MargAdh', 'SingEpiSize', 'BareNuc', 'BlandChrom', 'NormNucl', 'Mit' and 'Class' is the target column.

There is one row named ID which contains the ID number of the patients but it is not used to train the model.
