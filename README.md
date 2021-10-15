# Algoritmo_Logistics_Hackathon

Problem Statement:
Logistics in supply chain plays a crucial role in the inventory management of the raw materials required for the operations, The firm will like to make use of data driven approach 
using ML models so that they can predict which order can get delayed in the future and hence take preventive measures.

The objective is to get the highest F1 score for the class label 1 (orders getting delayed).

About the dataset:
The training data contains 126363 records while the test data contains 54156 records. There are 28 total features including the target class.

Following ML models have been used for prediction of the target class:
1. Random Forest
2. AdaBoost
3. XG Boost
4. Light GBM
5. CatBoost

Out of all the models, the Random forest classifier was selected as the best model as it provided the highest F1 score of 71.788 % on the test submission portal. The RF model was also used for feature selection.
