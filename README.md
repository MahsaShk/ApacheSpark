<h1>ApacheSpark</h1> 

This repository introduces **Pyspark by example** and provides solutions to some machine learning consulting projects.

Below is the list of the Pyspark materials:

<a href="pyspark-test.ipynb">Introduction to Pyspark RDD and DataFrame</a>

<a href="dataFrame-basics.ipynb">Details of Pyspark DataFrame</a>

<a href="PySpark-AWS-EC2.ipynb">How to setup Pyspark on Amazon AWS EC2 </a>

<a href="pyspark-MLlib.ipynb"> Introduction to Pyspark MLlib (Machine learning library) </a>

## Machine learning projects using Pyspark MLlib:

### <a href="Linear_Regression_Consulting_Project.ipynb"> Linear regression consulting project </a>:

In this project, parameter tunning using CrossValidator is used. Also, categorical features are handled.

### <a href="Logistic_Regression_Consulting_Project.ipynb"> Logistic regression consulting project </a>:

In this project, **imbalanced data** issue is resolved using weightCol in LogisticRegression. Also, a datetime feature is processed. StandardScaler was used to normalize each feature to unit standard deviation and zero mean.

### <a href="Tree_Methods_Consulting_Project.ipynb"> Tree methods consulting project (Decision tree, Random Forest, and GBT Classifiers)</a>:

This project focuses on feature importance computation. In this project, the **imbalanced data** issue is handled by using boosting techniques. In general, boosting algorithms are good choices for class imbalanced data.

For better results, one can use synthetic sampling methods like SMOTE and MSMOTE along with advanced boosting methods like Gradient boosting and XG Boost.



## References:

Apache Spark Documentation available at http://spark.apache.org/

Kaggle open datasets available at https://www.kaggle.com/docs/datasets

Spark and python for big data with pyspark, Udemy

Advanced Analytics with Spark, 2nd Edition, Sandy Ryza, Uri Laserson, Sean Owen, Josh Wills


