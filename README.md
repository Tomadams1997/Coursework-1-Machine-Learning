# Coursework-1-Machine-Learning

This repository contains a script to perform sentiment analysis on sets of positive and negative IMDB reviews.
The reviews are attatched split into Training, Development and Testing. These 3 are then again split into both Positive and Negative sets.
The machine learning model is build through using tf-idf selecting the top 850 features. 
Chi-squared statistics is then used to return the top 400 features in which a Linear, Polynomial and RBF model is trained.
The model is built on the Training data set and tested against the Testing data set.

## Requirements 
The document requires the use of an iPython IDE, the suggested IDE is Jupyter Notebooks.
This can be installed from the terminal using;
```
pip install notebook
```
To open the file within Jupyter Notebooks from the terminal, type into the terminal;
```
jupyter notebook part2code_C1621568.ipynb
```
The iPython document requires the following packages;
```
1. numpy
pip install numpy

2. pandas
pip install pandas

3. sklearn
pip install -U scikit-learn

4. nltk
pip install --user -U nltk
```
