# PROJECT TITLE 
Disease Symptom Prediction

## NON-TECHNICAL EXPLANATION OF YOUR PROJECT
A machine learning model based on symptoms of the patient. Given the type of symptoms that a person have, this model can help to properly classify and predict the type of disease of the patient and whether or not to send the patient to the hospital.

## DATA
The dataset used in this model includes the symptoms of the disease, severity of the symptoms and also the precaution based on the disease. This dataset is sourced from [kaggle](https://www.kaggle.com/datasets/itachi9604/disease-symptom-description-dataset?select=dataset.csv)

## MODEL 
Model used include a random forest classification which allows for a proper growing and pruning of the tree to correctly identify each diseases. Random Forest is used as this model allows for classification of multiple different categorical values. \
SVM is used based on the severity of the symptoms to determine whether or not the patient should be sent to the hospital. As SVM draws a boundary on the categorical target based on predictors, it is selected to determine whether or not the patient should be sent to the hospital

## HYPERPARAMETER OPTIMSATION
For random forest, the hyperparameter optimized in this model includes 'max_depth' - depth of the tree, 'max_features' - The number of features to consider when looking for the best split , 'min_samples_split' - The minimum number of samples required to split an internal node , 'n_estimators' - The number of trees in the forest. \
For SVM, the hyperparameter optimized includes 'C' - Regularization parameter. The strength of the regularization is inversely proportional to C, 'gamma'- Kernel coefficient , 'kernel' - type of kernal used , 'probability' - Whether to enable probability estimates.\
The model is optimized using a gridsearch technique that test the different parameters included.


## RESULTS
From the model, the random forest scored an average precision of 99% on the different type of diseases on the test dataset. For the SVM, it got a 100% accuracy on the test dataset. This may be due to the small sampling size of the dataset and will require more types of diseases to be included to have a better guage in the testing.

