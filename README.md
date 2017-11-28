# Breast-cancer-risk-prediction

> Necessity, who is the mother of invention. – Plato*

## Welcome to my GitHub repository on Using Predictive Analytics model to diagnose breast cancer.
---

### Objective:
The repository is a learning exercise to:
* Apply the fundamental concepts of machine learning from an available dataset
* Evaluate and interpret my results and justify my interpretation based on observed data set
* Create notebooks that serve as computational records and document my thought process. 

The analysis is divided into four sections, saved in juypter notebooks in this repository
1. Identifying the problem  and Data Sources
2. Exploratory Data Analysis
3. Pre-Processing the Data
4. Build model to predict whether breast cell tissue is  malignant or Benign

### [Notebook 1](https://github.com/ShiroJean/Breast-cancer-risk-prediction/blob/master/NB1_IdentifyProblem%2BDataClean.ipynb): Identifying the problem and Getting data.
**Notebook goal:Identify the types of information contained in our data set**
In this notebook I used Python modules to import external data sets for the purpose of getting to know/familiarize myself with the data to get a good grasp of the data and think about how to handle the data in different ways. 
### [Notebook 2](https://github.com/ShiroJean/Breast-cancer-risk-prediction/blob/master/NB2_ExploratoryDataAnalysis.ipynb) Exploratory Data Analysis
**Notebook goal:  Explore the variables to assess how they relate to the response variable** 
In this notebook, I am getting familiar with the data using data exploration and visualization techniques using python libraries (Pandas, matplotlib, seaborn. Familiarity with the data is important which will provide useful knowledge for data pre-processing)
### [Notebook 3](https://github.com/ShiroJean/Breast-cancer-risk-prediction/blob/master/NB3_DataPreprocesing.ipynb) Pre-Processing the data
**Notebook goal:Find the most predictive features of the data and filter it so it will enhance the predictive power of the analytics model.**
In this notebook I use feature selection to reduce high-dimension data, feature extraction and transformation for dimensionality reduction. This is essential in preparing the data before predictive models are developed.
### [Notebook 4](https://github.com/ShiroJean/Breast-cancer-risk-prediction/blob/master/NB4_PredictiveModelUsingSVM.ipynb) Predictive model using Support Vector Machine (svm)
**Notebook goal: Construct predictive models to predict the diagnosis of a breast tumor.** 
In this notebook, I construct a predictive model using SVM machine learning algorithm to predict the diagnosis of a breast tumor. The diagnosis of a breast tumor is a binary variable (benign or malignant). I also evaluate the model using confusion matrix the receiver operating curves (ROC), which are essential in assessing and interpreting the fitted model.

### [Notebook 5](https://github.com/ShiroJean/Breast-cancer-risk-prediction/blob/master/NB_5%20OptimizingSVMClassifier.ipynb): Optimizing the  Support Vector Classifier
**Notebook goal: Construct predictive models to predict the diagnosis of a breast tumor.** 
In this notebook, I aim to tune parameters of the SVM Classification model using scikit-learn.

