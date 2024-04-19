CONCEPTS USED FOR DATA PRE PROCESSING:

Natural language processing:


Machine learning data only works with numerical features so we have to convert text data into numerical columns. So we have to preprocess the text and that is called natural language processing.


In-text preprocess we are cleaning our text by steaming, lemmatization, remove stopwords, remove special symbols and numbers, etc. After cleaning the data we have to feed this text data into a vectorizer which will convert this text data into numerical features.
Dataset:
Our dataset consist of five columns where first four are the input features and the label column tells whether the news is real or fake.

Sample of the dataset is: 
![image](https://user-images.githubusercontent.com/118727786/218250897-cc426647-d8c9-42d1-ae4f-9e481eea5b04.png)

 Classification methods used:
 
 
Logistic regression:

Logistic Regression is much similar to the Linear Regression except that how they are used. Linear Regression is used for solving Regression problems, whereas Logistic regression is used for solving the classification problems.
In Logistic regression, instead of fitting a regression line, we fit an "S" shaped logistic function, which predicts two maximum values (0 or 1).
         
Passive Aggressive Classifier:

The  algorithm falls under the category of online learning algorithms, can handle large datasets, and updates its model based on each new instance it encounters.  The passive aggressive algorithm is an online learning algorithm, which means that it can update its weights as new data comes in. The passive aggressive classifier has a parameter, namely, the regularization parameter, C that allows for a tradeoff between the size of the margin and the number of misclassifications.

Support vector machines:
Support Vector Machine or SVM is one of the most popular Supervised Learning algorithms, which is used for Classification as well as Regression problems. It is used for Classification problems in Machine Learning.

The goal of the SVM algorithm is to create the best line or decision boundary that can segregate n-dimensional space into classes so that we can easily put the new data point in the correct category in the future. This best decision boundary is called a hyperplane.

SVM chooses the extreme points/vectors that help in creating the hyperplane. These extreme cases are called as support vectors, and hence the algorithm is termed as Support Vector Machine. Consider the below diagram in which there are two different categories that are classified using a decision boundary or hyperplane.
