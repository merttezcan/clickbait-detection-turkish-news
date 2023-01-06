# Detecting Misleading Headlines in Turkish News: A Study of Clickbait Detection

This project aims to detect clickbait headlines using machine learning techniques. The dataset used in this project is taken from [Kaggle](https://www.kaggle.com/datasets/suleymancan/turkishnewstitle20000clickbaitclassified).

# Requirements

To run this project, you need to have the following libraries installed:

- pandas
- numpy
- matplotlib
- seaborn
- re
- string
- nltk
- sklearn
- scipy

# Usage

To use this project, follow these steps:

Clone this repository:
```
git clone https://github.com/merttezcan/clickbait-detection-turkish-news.git
```

Navigate to the project directory:

```
cd clickbait-detection-turkish-news
```


Run the Jupyter notebook:
```
jupyter notebook
```

Follow the steps in the notebook to detect clickbait headlines.


# Results

We trained and tested several machine learning models, including Logistic Regression, Naive Bayes, Support Vector Machine, Random Forest, and XGBoost. The best performing model was Linear Support Vector Classifier, with an accuracy of 88%.

# Future Work

There are several ways we can improve the performance of our model:

- We can try using different feature engineering techniques to extract more meaningful features from the text.
- We can try using different vectorization techniques, such as Word2Vec or FastText.
- We can try using deep learning models, such as Long Short-Term Memory (LSTM) or Transformer.

# Conclusion

In this project, we successfully detected clickbait headlines using machine learning techniques. We also saw the importance of hyperparameter tuning and cross validation in improving the performance of our models. Further work can be done to improve the performance of our model even more.