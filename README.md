# Sentiment Classification with Random Forest

## Introduction

Random Forest algorithm is a powerful tree learning technique in machine learning. It works by creating a number of decision trees during the training phase. Each tree is constructed using a random subset of the data set to measure a random subset of features in each partition. This randomness introduces variability among individual trees, reducing the risk of overfitting and improving overall prediction performance.

A Random Forest Classifier is a powerful ensemble learning algorithm used for classification tasks. It operates by constructing multiple decision trees during training and outputting the class that is the mode of the classes (classification) or mean prediction (regression) of the individual trees. This method helps improve the predictive accuracy and control overfitting.

## Dataset

This experiment employs a dataset that comprises movie reviews. The dataset used for model training is publicly available on Kaggle and accessible for free on the internet. The link to this data is [Kaggle Rotten Tomatoes EDA](https://www.kaggle.com/code/stefanoleone992/rotten-tomatoes-eda). The movie reviews were annotated using [RoBERTa](https://github.com/bitacode/Labeling-Dataset-For-Sentiment-Analysis.git).

## Results

In the sentiment classification task using the Random Forest algorithm, the model achieved a test accuracy of 40.89%. This indicates that the model correctly classified sentiment labels for approximately 40.89% of the test data. While Random Forest is a powerful ensemble learning technique, this result suggests that it may not be the most effective method for this particular sentiment analysis task, potentially due to the complexity and nuances of natural language data.

## Prospects

Random Forest generally performs well on a wide range of classification tasks, especially those involving structured/tabular data. Its performance tends to be stronger in tasks where the features are well-represented as discrete or continuous variables, but it may struggle with more complex, unstructured data like raw text (e.g., in natural language processing tasks). This experiment was conducted to demonstrate this point, highlighting the limitations of Random Forest when applied to sentiment classification using text data.

Random Forest typically excels at imbalanced classification tasks like fraud detection, rare disease diagnosis, or spam detection, where one class significantly outnumbers another. This is because Random Forest can handle imbalanced datasets effectively, especially when paired with techniques like class weighting, SMOTE (Synthetic Minority Over-sampling Technique), or subsampling. These approaches could be explored in future experiments to improve performance on similar tasks.
