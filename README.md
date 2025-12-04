# Comp331Project
This repository contains the code and figures for my Comp 331 project  
The dataset I used can be found at https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud, and is titled creditcard.csv  
I used Google Colab to write and run my code, so upload the related code and csv to run it for yourself  
## Dataset overview  
The dataset for this project contains transactions made by European cardholders over two days in September of 2013  
The target variable, class, marks each transaction as either legitimate or fraudulent  
Among the features are two raw variables (time and amount), as well as twenty-eight PCA components  
It contains 284,807 transactions, with only 492 of them being labeled as fraudulent  
## Project description  
For this project, I focused on two features: Time & Amount  
I also engineered two more, named Hour & LogAmount  
The main part of the project involved training multiple ML models using logistic regression
* The first model used the raw data, with no scaling, no stratification, and no k-fold
* The second model used the deduplicated dataset, with scaling and a stratified split
* The third model used a stratified, 5-fold split
