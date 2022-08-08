# Permutation Feature Importance for ML Interpretability from Scratch

Code Repository for "Permutation Feature Importance for ML Interpretability from Scratch"

Use permutation feature importance to discover which features in your dataset are useful for prediction–implemented from scratch in python.

Full article: https://towardsdatascience.com/from-scratch-permutation-feature-importance-for-ml-interpretability-b60f7d5d1fe9

## Article Introduction
Advanced topics in machine learning are dominated by so-called black box models. As the name suggests, black box models are complex models where it's extremely hard to understand how model inputs are combined to make predictions. Deep learning models like artificial neural networks and ensemble models like random forests, gradient boosting learners, and model stacking could all be considered black box models that yield remarkably accurate predictions in a variety of domains from urban planning to computer vision. 

Diagram of a Black Box ModelOne drawback to using these black box models, however, is that it's often impossible to use traditional statistical inference to interpret how factors influence how predictions. This article will explain an alternative way to interpret black box models called permutation feature importance. Permutation feature importance is a powerful tool that allows us to detect which features in our dataset have predictive power regardless of what model we're using. 

We will begin by discussing the differences between traditional statistical inference and feature importance to motivate the need for permutation feature importance. Then, we'll explain permutation feature importance along with an implementation from scratch to discover which predictors are important for predicting house prices in Blotchville. We'll conclude by discussing some drawbacks to this approach and introducing some packages that can help us with permutation feature importance in the future.


