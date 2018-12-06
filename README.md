# Ensemble-Learning-and-Random-Forests
Chapter 9 of Hands On Machine Learning by Geron

In this chapter we look at a few methods of improving results: Voting Classifiers, Bagging and Pasting, Random Forests, and Boosting.

The voting classifier stacks models to improve predictive power and increase accuracy. This code is implemented on sklearn's make_moons dataset. We stack linear regression, random forest classifier, and a support vector classifier. We demonstrate that we can get better accuracy by using the voting classifier than we would using any individual method.

We then use a bagging classifier on sklearn's Iris dataset, to make leaf predictions based on leaf size. We then slightly alter the code to include out of bag classification.

We now implement the Random Forests classifier. From this code, we find which of the leaf's features (sepel length, sepel width, petal length, petal width) are the most important in making predictions.

We then implement boosting to further improve our model. However, this is likely to overfit, so we use a couple of early stopping techniques to prevent this.
