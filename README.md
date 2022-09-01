#Implementation of Linear Regression on the Iris Dataset
The Iris dataset was used in R.A. Fisher's classic 1936 paper, The Use of Multiple Measurements in Taxonomic Problems, and can also be found on the UCI Machine Learning Repository.

It includes three iris species with 50 samples each as well as some properties about each flower. One flower species is linearly separable from the other two, but the other two are not linearly separable from each other.

The columns in this dataset are:

* Id
* SepalLengthCm
* SepalWidthCm
* PetalLengthCm
* PetalWidthCm
* Species

The input features used for the model are:

* SepalLengthCm
* SepalWidthCm
* PetalLengthCm
* PetalWidthCm

The ouput feature * Species

In this project, with the help of the Linear Regression algorithm from
Scikit-Learn, the dataset is plitted into testing and training set with 
20% being used for testing and 80% for training the model. After training
the model, the model score, that is, R^2, for the data was 0.9115961491141747.

The model is also being implented mathematically using the model:
f(x) = w*x + b, where x is the input feature(s), w and b being the 
parameters of the model.

Some visualization are also being done in this project to visually comprehend the vast amount of data at a glance and in better way.

Lastly, the features of the data were being re-scaled to reduced any data outliers and to correct features varying in some degrees of magnitude, range and unit.