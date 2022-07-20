# Password-Strength-Classifier-NLP

## Project Objective
To build a password strength classifier that classifies password's strength to be either low, average or high.

## Methods used preprocessing
The data used for this project was extracted from an API and was preprocessed using python libraries. 
Data preprocessing and visualization was carried out and it was seen that the data was an imbalanced data which could result to a bias prediction.
The data was further converted into vector representation using TF-IDF vectorizer to determine the relevance of each word and python's imblearn module was used 
to deal with the imbalanced data.

## Model Building
The data was further divided into train data and test data to avoid overfitting and underfitting.
Train data to learn the relationship within the data and test data will be unseen by the model and will the used to test the model.
The model was initially built using LogisticRegression which resulted to an accuracy of 80%.
For better accuracy, the model was built using RandomForestClassifier with an accuracy of 97%.

## Is the model Optimal for predictions?
Yes!!!
The model is optimal for predictions and can be used as a model for other preprocessed classification datasets.
