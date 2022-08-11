# Abstract
This project used data collected from an online drug review website to conduct exploratory data analysis, sentiment classification and topic modelling. The first part explores the conditions people treat with antidepressants, identifies the periodicity of different conditions and the antidepressants that are most commonly used or got the highest average rating. In the second part, different feature extraction techniques are used to convert textual data to numerical values. In the sentiment classification part, the reviews are labeled as ‘positive’, ‘negative’ or ‘neutral’ using the ratings. Machine learning algorithms including logistic regression, SVM, multinomial Naïve Bayes and XGBoost are then used to predict the sentiment in the reviews, metrics including accuracy, AUC and weighted average f-1 score are applied to evaluate model performance, and feature selection and ensemble learning are used to improved model performance. In the topic modelling part, four topics are identified using LDA.

# Methods

## Feature Extraction
* Bag-of-Words
* TF-IDF
* Word2Vec
* Doc2Vec

## Classification
* Multinomial Naive Bayes
* SVM
* Random Forest
* XGBoost
* Ensemble Learning

## Topic Modeling
* LDA

# Conclusion
TF-IDF were found to be the most effective approach to convert textual data to numerical values. XGBoost got the highest accuracy (0.80) and F1-score (0.79) while logistic regression and SVM also showed high prediction power on the sentiment. Ensemble learning with logistic regression, SVM and XGBoost improved the final accuracy by 1%. In the topic modeling part, the four topics identified are related to the conditions, side effect, life change and other, respectively.
