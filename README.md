# DES-CCF-Detection

This project uses Dynamic Ensemble Selection (DES) to detect credit card fraud.

The dataset used can be accessed from [Kaggle](https://www.kaggle.com/datasets/dhanushnarayananr/credit-card-fraud).

DESlib is an easy-to-use ensemble learning library focused on the implementation of the state-of-the-art techniques for dynamic classifier and ensemble selection. The library is is based on scikit-learn, using the same method signatures: fit, predict, predict_proba and score. All dynamic selection techniques were implemented according to the definitions from [1].

This model consists of the following classification algorithms:
* Decision Trees
* Random Forest
* XGBoost
        
From the DESlib, the following techniques were used to create the proposed ensemble model:
* K-Nearest-Oracle-Eliminate (KNORA-E) [2]
* K-Nearest-Oracle-Union (KNORA-U) [2]
* Dynamic Ensemble Selection-Performance(DES-P) [3]
        
To evaluate the performance of the model, the following performance measures were used:
* Accuracy
* Precision
* F1 score
* Recall
* AUC
