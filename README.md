<h1>ApacheSpark</h1> 

This repository introduces **Pyspark by example** and provides solutions to some **machine learning consulting projects**. The Spark version 3.0.0 was used in this repository.

### List of Pyspark materials:

<a href="pyspark-test.ipynb">Introduction to Pyspark RDD and DataFrame</a>

<a href="dataFrame-basics.ipynb">Details of Pyspark DataFrame</a>

<a href="PySpark-AWS-EC2.ipynb">How to setup Pyspark on Amazon AWS EC2 </a>

<a href="pyspark-MLlib.ipynb"> Introduction to Pyspark MLlib (Machine learning library) </a>

## Machine learning projects using Pyspark ML library:

### <a href="Linear_Regression_Consulting_Project.ipynb"> Linear regression consulting project </a>:

In this project, parameter tunning using CrossValidator is used. Also, categorical features are handled.

### <a href="Logistic_Regression_Consulting_Project.ipynb"> Logistic regression consulting project </a>:

In this project, **imbalanced data** issue is resolved using weightCol in LogisticRegression. Also, a datetime feature is processed. StandardScaler was used to normalize each feature to unit standard deviation and zero mean.

### <a href="Tree_Methods_Consulting_Project.ipynb"> Tree methods consulting project (Decision tree, Random Forest, and GBT Classifiers)</a>:

This project focuses on feature importance computation. In this project, the **imbalanced data** issue is handled by using boosting techniques. In general, boosting algorithms are good choices for class imbalanced data.

For better results, one can use synthetic sampling methods like SMOTE and MSMOTE along with advanced boosting methods like Gradient boosting and XG Boost.


### <a href="Recommender_System_Project.ipynb"> Recommender system project</a>:

This project provides recommendation on [movielens dataset](https://grouplens.org/datasets/movielens/) based on collaborative filtering approach.


### <a href="NLP_Project.ipynb"> Natural Language Processing (NLP) project</a>:

In this project, an SMS Spam detection is designed using <a href="NLP_Tools.ipynb"> spark NLP tools</a>.

Introduction to Spark NLP tools along with some examples are presented <a href="NLP_Tools.ipynb"> here</a>.

The design pipline includes: **RegexTokenizer**, **StopWordsRemover**, **TF-IDF** based feature extraction, Naive Bayes classifier.

## References:

[1] Apache Spark Documentation available at http://spark.apache.org/

[2] Kaggle open datasets available at https://www.kaggle.com/docs/datasets

[3] Spark and python for big data with pyspark, Udemy

[4] Advanced Analytics with Spark, 2nd Edition, Sandy Ryza, Uri Laserson, Sean Owen, Josh Wills


<!-- Frequent pattern mining -->
