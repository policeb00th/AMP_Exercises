# Week 2
Install sci
py and sklearn on your system using 
```
pip install scipy, sklearn
```
## Regularization
Take a moment to go through the data in 'ex2data2.txt' as that is the data we'll be using for the regularization problem.
Here the data is shown of whether a microchip is of quality or not.
The first column contains the results of tests it underwent for test 1.
The second column contains the results of tests it underwent for test 2.
The third column shows whether it was selected or rejected.

The components for the exercise is given below:

* __regularizationmain.py__
The main file for the program, which will be using other files to  run the program.
An important difference is the use of feature mapping to increase the number of features. This is done to generate more features from existing ones, since the data we're fitting is non linear hence a line will never be able to fit it.
To enable this, we include the features and their polynomials raised to the sixth power as features too.

* __costFunctionReg.py__
The file contains the cost function that needs to be completed by you, keep in mind to use the regularization forumla.
The gradient function has already been completed for your ease.

# Sklearn implementation
The Sklearn libary is a boon to the community of machine learning, as it tremendously simplify the amount of code we have to write to achieve an accurate model. 
* __sklearn_log.py__
Contains the sklearn implementation of the Logistic regression problem we've implemented. Please go through it as it'll show you how our vast and multi file program reduces to merely 20 lines of code. Sklearn by default takes care of a lot of things for us, but allows us to customise functions as per our need. 
Read the documentation about sklearn and try implemting our previous exercises using sklearn


