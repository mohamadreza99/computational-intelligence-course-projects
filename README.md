# computational-intelligence-course-projects

## Adults Income Prediction
In this project, I used well-known [adults](https://sci2s.ugr.es/keel/dataset.php?cod=192#sub1) dataset. 


The Adult data set was extracted in 1994 from census data of the United States. It contains continuous and nominal attributes, describing some social information (age, race, sex, marital status, ...) about the citizens registered.

The task is to predict whether the citizen’s income exceeds fifty thousand dollars a year.

I implemented SVM algorithm with the help of sklearn library. in another implementation, I implemented KNN algorithm without the aid of any library or pre-written function.

A html file in the directory of this project exists that shows dataset characteristics and one can use it for EDA purposes. How to generate this file is demonstrated in the notebook.
<hr/>

## Covid 19 Patients Prediction
In this project, the goal is to predict the patients number regarding to the covid 19 pandemy in Iran. I used linear regression at first to find the best linear equation that fits this data graph. Improvement of algorithm is progressed by using Gradient Descent algorithm.

Furthermore, I used a polynomial regression algorithm to find the best degree of equation which fits on this data. All these algorithms implemented without using libraries and from scratch.
<hr/>

## Dogs Pics Classification
This task is to classify dogs pictures in different classes related to their breeds. Dataset in this project is [ImageNetDogs](http://vision.stanford.edu/aditya86/ImageNetDogs/) which prepared by Stanford University.

I used Transfer Learning with the help of TorchVision methods to construct a deep nueral network based on transfered weights of ResNet18.
