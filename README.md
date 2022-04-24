# Credit Card Fraud Prediction 💳
### 信用卡交易数据集 分析预测 ・ Prédiction de fraude par carte de crédit ・ Predicción de fraude con tarjeta de crédito ・ Предсказание мошенничества с кредитными картами ・ التنبؤ بالاحتيال على بطاقة الائتمان 
---

### About

This is a Mini-Project for SC1015 - Intro to Data Science and Artificial Intelligence. <br>
We used [Simulated Credit Card Transactions Generated Using Sparkov](https://www.kaggle.com/datasets/kartik2112/fraud-detection) as our dataset. <br>
You can access our code in the following order to understand it best:

> 
> 1. [Data Encoding, Resampling and Splitting](https://github.com/capnhayfay/DSAI-BCF2-G1/blob/main/Data%20Extraction%2C%20Resampling%2C%20and%20Splitting.ipynb)
> 
> 2. [Exploratory Data Analysis, Data Visualisation](https://github.com/capnhayfay/DSAI-BCF2-G1/blob/main/Data%20Visualizations.ipynb)
> 
> 3. [K-Nearest Neighbours Classification](https://github.com/capnhayfay/DSAI-BCF2-G1/blob/main/K-Nearest%20Classification.ipynb)
> 
> 4. [Random Forest Regression](https://github.com/capnhayfay/DSAI-BCF2-G1/blob/main/Random%20Forest.ipynb)
> 

### Contributors

- @Beelzebulb - EDA, K-Nearest Neighbours
- @capnhayfay - Data Encoding, Resampling & Splitting, Random Forest
- @tdxj2020 - Data Preparation, Cleaning, General Deliverables

### Problem Definition

- How are we able to predict if a credit card transaction is fraudulent?
- Which model would be the best to predict it?

### Models Used

1. KNN Classification
2. Random Forest Classification

> We contemplated on using Decision Trees, but they remain unused for this mini-project.

### Insights

- CC transaction amount distribution varies significantly between fraud, non-fraud transactions
- Customer-Merchant distance is similar for both fraud, non-fraud transactions
- Most fraudulent CC transactions occur on the weekends 💸💳
- The job with the most fraudulent CC transactions for this dataset is *Materials Engineer*
- The city with the most fraudulent CC transactions for this dataset is *Houston, TX* 🦅 

### Conclusion

- KNN classification had 96% accuracy, 6% precision, 58% recall, 0.11 F1-Score
- Random Forest classification had 99% accuracy, 76% precision, 11% recall, 0.20 F1-Score
- Based on the above results, KNN is better at detecting fraudulent in unknown transaction datasets <br>
  due to higher recall 
- SMOTE is good for balancing an imbalanced dataset, but will adversely affect the metrics of <br>
  classification models trained with SMOTE-adjusted datasets on test datasets. (Recall, F1-score)

### What did we learn from this project?

- Utility, importance of encoding categorical variables in modelling (CatBoost, Binary encoding)
- Managing highly imbalanced data using Synthetic Minority Oversampling Technique (SMOTE)
- Random Forest Classification, K-Nearest Neighbours (KNN) Classification with sklearn
- Analysing effectiveness of classification techniques with Recall, F1 Score, visualised with confusion matrix
- Understanding classification results (decision trees etc.), then applying them to data
- Collaborating using GitHub, other collaborative digital platforms

### Data Used
- All of our datasets are stored withn a [dropbox folder](https://www.dropbox.com/sh/9i76ymyhqhl53pa/AAA5zYYpmbxEsLgxfpzoAQqQa?dl=0).
- We wanted to use github's LFS system however that kept leading to errors hence, the workaround

### References

- https://www.analyticsvidhya.com/blog/2021/10/an-introduction-to-random-forest-algorithm-for-beginners/
- https://towardsdatascience.com/machine-learning-basics-random-forest-regression-be3e1e3bb91a
- https://towardsdatascience.com/smarter-ways-to-encode-categorical-data-for-machine-learning-part-1-of-3-6dca2f71b159
- https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.Normalizer.html#sklearn.preprocessing.Normalizer
- https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html
- https://scikit-learn.org/stable/modules/classes.html#module-sklearn.metrics
- https://scikit-learn.org/stable/modules/classes.html#module-sklearn.preprocessing
- [Slides] https://slidesgo.com/theme/neon-marketing-plan#search-Marketing&position-11&results-1040
- [Image] <https://geopy.readthedocs.io/en/stable/_images/logo-wide.png>
- [Image] <https://upload.wikimedia.org/wikipedia/commons/thumb/9/91/Octicons-mark-github.svg/2048px-Octicons-mark-github.svg.png>

<!--- add more references! -->

<!--https://www.markdownguide.org/basic-syntax/-->
