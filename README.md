# Mobile_dataset
the purpuse of this project to build a machine learning model on a mobile dataset to predict the cost (low ,medium ,high ,very high) from given specification of mobile.

## Goals of the Project:

1. Get the dataset .
2. Clean the dataset with python and pandas framework.
3. Deal with the missing values if any present in the dataset.
4. Visualize the dataset with various plot types.
5. Get insights from the dataset after EDA.
6. With the help of EDA insights make dataset ready for the model building.
7. Split the dataset into Train and Test data. and prepare train and test data for machine learning model.
8. Try all the base model as well some of the enesemble model on train set and evaluate the model with the help of Sklearn framework.
9. Choose the few better working models with respect to this dataset. na do the cross validation and tunnig the models.
10. Finally check all the tune models on the test dataset and choose the best model for our dataset on the basis of right evaluation.


## Outline
1. Materials and methods
2. General part :   i) Libraries import  ii) Dataset exploration  iii) Deal with missing values iv) Clean the dataset  iv) Visualization with differnt plots  v) getting insights
3. Tasks : i) Web Scrapping ii)EDA iii) model Building.

    
## Materials and methods: 
The data that we are going to use for this project is already given in the repository.

About this Dataset: 

mobile dataset consist the specication of mobile along with the cost . In the mobile dataset we have  2000 instances and 15 features. This tabular dataset consists  features like battery power, front camera specs, ram, talk time , internal memory, etc

## Task
In this project, with the help of EDA insights we will build a machine learning model.


1. EDA

  we will clean the data and doing some basic EDA and visulization plots we will write some insights.

  We will try to answer following quetions :
  
    1. how device pricing is influenced by mobile body and display dimensions?
    
    2. how device pricing is influenced by mobile camera features?
    
    3. how device pricing is influenced by mobile features related performacnce?
    
    4. how device pricing is influenced by battery power and talk time?
    

2. MODEL BUILDING

  with the help of sklearn library we will try to build a model such that it predicts the cost (low ,medium ,high ,very high) from given specification of mobile.

  machine learning model we tried for the dataset :

    1. LogisticRegression
    2. KnearestNeighbour
    3. SVM
    4. DecisionTree
    5. RandomForeset
    6. GradientBoosting
    7. ExtraTree
    8. Adaboost
    9.Xgboost

## USED LIBRARIES:
1. NUMPY
2. PANDAS
3. MATPLOTLIB
4. SEABORN
5. SKLEARN
   

