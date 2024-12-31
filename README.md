**EFFICIENCY COMPARISON OF GRADIENT BOOSTING AND ADAPTIVE BOOSTING FOR TWEET SENTIMENT ANALYSIS**

**Introduction**

This project aims to compares the efficiency of Gradient Boosting machine (GBM) and Adaptive
Boosting (AdaBoost) models. It also describes the methods and results of the comparison. By
applying these two boosting algorithms to tweet sentiment analysis ,the investigation sought to
ascertain how well they performed in terms of accuracy and robustness.

**Approach**

**Data Preprocessing**

Standard data and text preprocessing techniques were applied to the dataset , that included:
handling missing values , removal of URLs, special characters and numbers, tokenization ,
lowercasing, lemmatization and stopword removal. NLTK library was used for text
preprocessing to ensure the dataset was cleaned and prepared for analysis.

**Homogeneous Machine Learning Model**

To preserve model homogeneity , decision trees were used as base estimators in both the GBM
and AdaBoost models. Homogeneity ensures consistency and simplifies the comparison between
various models.

**Improving Accuracy and Robustness**

To optimize parameters like learning rate and number of estimators ,hyperparameter tuning was
performed for both GBM and AdaBoost models. This involves finding the optimal values for
these parameters to improve the performance of the model.

**Model Training and Evaluation**

In model training ,patterns and correlations within the training data are discovered by fitting the
model to the data .By employing a different set of test data, evaluation ,on the other hand,
evaluates how well the trained model performs. Using the preprocessed tweet dataset both GBM
and AdaBoost models were trained. Accuracy score was used as the evaluation metric to
compare the performance of both models.

**Efficiency Comparison of Results**

The accuracy scores of both models were compared .The accuracy scored obtained were:
Gradient Boosting Machine : 75%
Adaptive Boosting :72%
Thus GBM outperforms the Adaboost model for tweet sentiment analysis due to higher accuracy.
