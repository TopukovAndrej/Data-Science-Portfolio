# Data Science Portfolio
This repository contains all of my data science projects that I have created in my free time for self learning purposes. Other projects may be added as well.


**Natural Language Processing**
---

- [SMS Ham/Spam Classification](https://github.com/TopukovAndrej/Data-Science-Portfolio/blob/main/.ipynb%20Notebooks/SMS%20Classification.ipynb)

The goal of this project was to classify SMS messages as ham or spam. I have used several techniques to preprocess the messages and used several techniques to obtain feature 
vectors (Bag of Words, TF-IDF vectors and Keras Tokenizer). To classify the messages, I used several ML models, such as Logistic Regression, Random Forest classifier and Support 
Vector Machines (SVM). Also, I created a Deep Learning model - RNN, that gave the best results (as expected). The ML models gave better results with the TF-IDF vectors, than 
with the Bag of Words vectors.

Dataset was obtained from: [https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection](https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection)

Dataset Reference: [https://www.dt.fee.unicamp.br/~tiago/smsspamcollection/](https://www.dt.fee.unicamp.br/~tiago/smsspamcollection/)

**Machine Learning**
---

- [Wine Classification](https://github.com/TopukovAndrej/Data-Science-Portfolio/blob/main/.ipynb%20Notebooks/Wine%20Classification.ipynb)

In this project the goal was to find from which one of the three possible cultivars a wine was derived. I also did some Exploratory Data Analysis (EDA) by searching the data for 
NaN
values, searching for duplicate entries, checking data types etc. I managed to extract some useful data from the dataset, such as average alcoholic percentage of wine derived 
from each of the three cultivars, which cultivar gives the wine with the highest/lowest color intensity, which cultivar gives the wine with the highest/lowest protein 
concentration etc. In the end I used two ML models for the classification, k-Nearest Neighbors and Decision Tree. k-Nearest Neighbors gave better results.

Dataset was obtained from: [https://archive.ics.uci.edu/ml/datasets/wine](https://archive.ics.uci.edu/ml/datasets/wine)

Dataset Reference: Dua, D. and Graff, C. (2019). UCI Machine Learning Repository [http://archive.ics.uci.edu/ml]. Irvine, CA: University of California, School of Information and 
Computer Science.

- [Iris Classification](https://github.com/TopukovAndrej/Data-Science-Portfolio/blob/main/.ipynb%20Notebooks/Iris%20Classification.ipynb)

This is a very simple project in which I did some data analysis and exploration and also extracted some useful information. The dataset used is the famous Iris 
dataset. In the end, I classified the data samples using two classification models, a Multi Layer Perceptron and a Gaussian Naive Bayes. Better results were obtained 
using the Gaussian Naive Bayes model, although I did not use hyperparameter optimization for the MLP model.

Dataset was obtained from: [https://archive.ics.uci.edu/ml/datasets/Iris](https://archive.ics.uci.edu/ml/datasets/Iris)

Dataset Reference: Dua, D. and Graff, C. (2019). UCI Machine Learning Repository [http://archive.ics.uci.edu/ml]. Irvine, CA: University of California, School of 
Information and Computer Science.
