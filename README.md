# Welcome to Credit Card Fraud Prediction

## About

This is a Mini-Project for SC1015 - Intro to Data Science and Artificial Intelligence
Our data was [Simulated Credit Card Transactions generated using Sparkov](https://www.kaggle.com/datasets/kartik2112/fraud-detection).
For detailed walkthrough, please view the source code in order from:

1. [Data Encoding, Resampling and Splitting](https://github.com/capnhayfay/DSAI-BCF2-G1/blob/main/Data%20Cleaning%20and%20Resampling.ipynb)
2. [Data Visualization](https://github.com/capnhayfay/DSAI-BCF2-G1)
4. [K-Nearest Neighbours Classification](https://github.com/capnhayfay/DSAI-BCF2-G1)
5. [Random Forest Regression](https://github.com/capnhayfay/DSAI-BCF2-G1/blob/main/)

## Contributors

- @Beelzebulb - EDA, K Nearest Neighbours
- @capnhayfay - Logistic Regression
- @tdxj2020 - Data Visualization, Data Extraction

## Problem Definition

- Are we able to predict if a Credit Card Transaction is Fraudulent?
- Which model would be the best to predict it?

## Models Used

1. KNN Classification
2. Random Forest 

## Conclusion

- Popularity and budget have low linear correlation value with ratings (watch out for bandwagons 🤣)
- Popularity of the casts and crews have higher linear correlation value with ratings
- Resampling imbalanced data improved model performance especially on the minority class
- Logistic Regression did not perform well with non-linearly correlated variables
- Neural Networks along with SMOTEENN resampling method consistently did well in predicting good movies after 100 training attempts (around 72% accuracy, 70% recall)
- Yes, it is possible to predict if a movie is good with acceptable amount of accuracy and recall

## What did we learn from this project?

- Handling imbalanced datasets using resampling methods and imblearn package
- Neural Networks, Keras and Tensorflow
- Logistic Regression from sklearn
- API Usage
- Other packages such as tqdm, json, requests
- Collaborating using GitHub
- Concepts about Precision, Recall, and F1 Score

## References

- <https://developers.themoviedb.org/3/getting-started>
- <https://www.free-powerpoint-templates-design.com/old-style-movie-projector-powerpoint-templates/>
- <https://www.kaggle.com/rafjaa/resampling-strategies-for-imbalanced-datasets>
- <https://alexlenail.me/NN-SVG/index.html>
- <https://www.kdnuggets.com/2016/08/learning-from-imbalanced-classes.html/2>
- <https://arxiv.org/pdf/1608.06048.pdf>
- <https://machinelearningmastery.com/tutorial-first-neural-network-python-keras/>
- <https://towardsdatascience.com/derivative-of-the-sigmoid-function-536880cf918e>
- <https://www.researchgate.net/figure/Calculation-of-Precision-Recall-and-Accuracy-in-the-confusion-matrix_fig3_336402347>
- <https://medium.com/analytics-vidhya/confusion-matrix-accuracy-precision-recall-f1-score-ade299cf63cd>
