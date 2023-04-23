# PROJECT TITLE 

### Machine Learning Optimization for Credit Analysis

## NON-TECHNICAL EXPLANATION OF YOUR PROJECT

The objective of this model is to analyse the potential of ML algorithms in the context of credit risk. 
In particular, the project has the ambition to build a model that is able to predict the outcome for the potential granting of a loan by classifying customers into good/bad according to the probability of default.
In order to achieve this goal, different algorithms are tested during the project and among them the most promising ones are chosen to pass to the optimisation phase, ultimately choosing the best one.

## DATA

The original dataset contains 1000 entries with 20 categorial/symbolic attributes prepared by Prof. Hofmann. 
In this case the dataset is reduced removing some features totaling in 10 feature 4 numerical and 6 categorical.
Each entry represents a person who takes a credit by a bank where each person is classified as good or bad credit risks according to the set of attributes. 
The link to the original dataset can be found below.

https://archive.ics.uci.edu/ml/datasets/Statlog+%28German+Credit+Data%29

## MODEL 

the model selected after comparison with other candidates is the random forest.

## HYPERPARAMETER OPTIMSATION

The technique for optimising hyperparameters is Bayesian optimisation

## RESULTS

The results obtained are very poor and do not allow one to hope for a real-world implementation of the model, effectively limiting its use to purely academic purposes.

Below are some metrics used to measure performance:

Accuracy:0.708

Precision:0.2361111111111111

Recall:0.4857142857142857

F1 Score:0.3177570093457944

