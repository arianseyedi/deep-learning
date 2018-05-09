# Welcome to notMNIST project

Here I breifly explain to you the motive for this project.
* **About the project:** Simply put, in this project we train a model to identify a number of alphabetic letters. For that we use an extensive set of graphical data containing the letters (classes thereafter) written in unique fonts, balanced in number across each class. We represent this data numerically using numpy arrays and then randomize them to make sure that the model is not trained one whole class at a time as that would ruin the accuracy of our predictive model.  
* **About the name:** MNIST is the name of a [famous data set](http://yann.lecun.com/exdb/mnist/) of more than 60,000 handwritten diggits. In this project, we instead use many different representations of *alphabetic* letters A(a)-J(j). So, notMNIST!
* **Notes:** In this project the technique used is called Multinomial Logistic Classification which denotes the process of turning data into one-hot coded vectors. Cross Entropy is then applied to minimize the loss (i.e. training process). The sklearn package is used for model training. 
