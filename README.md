# WineQualityTesting_PY-ML
The aim of this case study is to predict wine quality based on physicochemical data.

In this study a large dataset was taken from the UC Irvine Machine Learning Repository which included 4898 instances of white wine with 11 physicochemical data.
In this, I learnt how to use different models of machine learning to classify the wines as well as figure out the importance of each chemical analysis parameters in the wine and which to ignore.
This case study helped me understand how to perform data analysis using machine learning and python programming language.


## Data Description
The data of the white wine samples was taken from UC Irvine Machine Learning Repository.

The repoitory contains two datasets are related to red and white variants of the Portuguese "Vinho Verde" wine. Due to privacy and logistic issues, only physicochemical (inputs) and sensory (the output) variables are available (e.g. there is no data about grape types, wine brand, wine selling price, etc.).

These datasets can be viewed as classification or regression tasks. The classes are ordered and not balanced (e.g. there are many more normal wines than excellent or poor ones). Outlier detection algorithms could be used to detect the few excellent or poor wines. Also, we are not sure if all input variables are relevant. So it could be interesting to test feature selection methods.


## Attribute Information
Input variables (based on physicochemical tests):
1 - fixed acidity
2 - volatile acidity
3 - citric acid
4 - residual sugar
5 - chlorides
6 - free sulfur dioxide
7 - total sulfur dioxide
8 - density
9 - pH
10 - sulphates
11 - alcohol
Output variable (based on sensory data):
12 - quality (score between 0 and 10)


## Literature Survey
1. P. Appalasamy discussed about modeling the complex human taste is an important focus in wine industries. The main purpose of this study was to predict wine quality based on physicochemical data. This study was also conducted to identify outlier or anomaly in sample wine set in order to detect adulteration of wine.
2. Shen Yin evaluated that the quality prediction models are constructed based on multivariate statistical methods, including ordinary least squares regression(OLSR), principal component regression (PCR), partial least squares regression (PLSR), and modified partial least squares regression (MPLSR).
3. Dimitrija Angelkov introduced data mining technology for wine analysis. This paper made an analysis of data from the measurements in order to find hidden laws and relationships between the data. 


## Relevant papers
P. Cortez, A. Cerdeira, F. Almeida, T. Matos and J. Reis. Modeling wine preferences by data mining from physicochemical properties.
In Decision Support Systems, Elsevier, 47(4):547-553, 2009.


## Citation

Dua, D. and Graff, C. (2019). UCI Machine Learning Repository [http://archive.ics.uci.edu/ml]. Irvine, CA: University of California, School of Information and Computer Science.

P. Cortez, A. Cerdeira, F. Almeida, T. Matos and J. Reis.
Modeling wine preferences by data mining from physicochemical properties. In Decision Support Systems, Elsevier, 47(4):547-553, 2009.



## Note:

This case study was done as a final project for Python programming course included in the minor specialization of Artificial Intelligence for 5th semester.
In this I used Decision Tree, Support Vector Classifier, Random Forest and K-Nearest Neighbour to predict the quality of the white wine.
Learning outcome is understand Machine Learning concepts.
