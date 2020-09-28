# Assignment 1: Implementing a Classifier (due 10/5)

This assignment is to be completed by teams of 1-2 students.  You are not allowed to share your source code with other students outside your team.  The assignment is worth a total of 100 points.

The primary goal is to understand supervised learning and *decision tree* classification and apply these concepts to two different datasets.  To this end, you will implement the classifier from scratch.

> If you have any questions, visit us during office hours and/or post those questions on Piazza using the appropriate folder tag.

## Decision Trees

You will implement the `Decision Tree` learning algorithm presented in lectures and use the **information gain** as the split criterion.  Your implementation should use Python as the programming language and be clearly visible in an `Jupyter Notebook`.  You are free to pick any library to support your implementation (e.g. for handling data or dealing with math calculations) but you cannot use any functions that offer a *decision tree* implementation.  Feel free to design your own functions and/or classes to this end.  Your implementation should provide at least two functions/methods: `train` and `predict`, where the first trains a decision tree model with training data and the second returns the predicted labels for new data.

## Datasets

In order to test your implementation you will apply the decision trees to the following datasets:

- [Titanic Data Set](./titanic.csv), where each row represents one person.  Attributes to describe a person include whether they survived (this is the class/label), age, passenger-class, gender, number of siblings and parents aboard, and the fare paid.
- [Car Evaluation Data Set](https://archive.ics.uci.edu/ml/datasets/Car+Evaluation)

> A basic step in analyzing the data can be carried by looking with more details into features/attributes.  Are features discrete? continuous?  Do they contain N/A values?

## What to submit?

You will submit a single archive named `decision-trees.ipynb` to Gradescope.  Make sure you successfully **run all cells** prior to uploading your solution.

The notebook should contain (at least) the following sections:

1. Decision tree implementation (provide an abstract explaining your solution followed by cells with the classes or functions that implement your decision tree) - **40 pts**
2. Experiments with the `titanic` dataset (data preprocessing and analysis, as well as accuracy reports on both training and test data) - **30 pts**
3. Experiments with the `car evaluation` dataset (data preprocessing and analysis, as well as accuracy reports on both training and test data) - **30 pts**

> You must be reminded that students caught cheating or plagiarizing will receive `no credit`.  Additional actions, including a failing grade in the class or referring the case for disciplinary action, may also be taken.
