📘 Decision Tree Classifier and Regressor

Welcome to the Decision Tree Machine Learning Project!
This repository contains an easy-to-understand, practical demonstration of building and tuning Decision Tree models for both classification and regression tasks using scikit-learn.

🧬 What is a Decision Tree?

A Decision Tree is a supervised learning algorithm that works for classification and regression by learning simple decision rules from data features.

Each internal node: a "decision" on a feature.

Each leaf node: a prediction outcome.

Flow from root to leaf: model's decision-making process.

It's like asking a series of yes/no questions to guess the answer!

🧠 How It Works: Theory and Math

Classification Trees:

Try to split data into "pure" groups using metrics like Gini Impurity or Entropy.
Gini = 1 - sum(p_i^2)

Example: "Is Age < 30?" splits into two branches.

Regression Trees:

Splits minimize variance (MSE: Mean Squared Error) in target variable.

Gini Impurity (for classification)
MSE = (1/n) * sum((y_i - y_hat)^2)


Where  is the probability of class  at a node.

Mean Squared Error (for regression)



Where  are actual and  are predicted values.

📈 Why Decision Trees?

Easy to understand and visualize

No need for feature scaling

Can handle both numerical and categorical data

Can model non-linear relationships

Can easily overfit (so pruning/tuning is important)
