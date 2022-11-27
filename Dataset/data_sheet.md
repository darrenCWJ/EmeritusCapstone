# Datasheet Template

As far as you can, complete the model datasheet. If you have got the data from the internet, you may not have all the information you need, but make sure you include all the information you do have. 

## Motivation

- For what purpose was the dataset created? 

A dataset to provide the students a source to create a healthcare related system.
A project on the same using double Decision Tree Classifiication is available at : https://github.com/itachi9604/healthcare-chatbot
Get_dummies processed file will be available at https://www.kaggle.com/rabisingh/symptom-checker?select=Training.csv

- Who created the dataset (e.g., which team, research group) and on behalf of which entity (e.g., company, institution, organization)? Who funded the creation of the dataset?

Pranay Patil (Owner)

 
## Composition

- What do the instances that comprise the dataset represent (e.g., documents, photos, people, countries)? 

1. symptom_precaution.csv
       - ['Disease', 'Precaution_1', 'Precaution_2', 'Precaution_3',
       'Precaution_4']
       - Type of disease, precaution of the disease

2. symptom_Description.csv
       - ['Disease', 'Description']
       - Type of disease, description of the disease


3. dataset.csv
       - ['Disease', 'Symptom_1', 'Symptom_2', 'Symptom_3', 'Symptom_4',
       'Symptom_5', 'Symptom_6', 'Symptom_7', 'Symptom_8', 'Symptom_9',
       'Symptom_10', 'Symptom_11', 'Symptom_12', 'Symptom_13', 'Symptom_14',
       'Symptom_15', 'Symptom_16', 'Symptom_17']
       - Type of disease, symptoms of the diseases

4. Symptom-severity.csv
       - ['Symptom', 'weight']
       - Type of symptoms, severity of the symptoms in weights



- How many instances of each type are there? 

1. symptom_precaution.csv
41

2. Sympton_Description.csv
41

3. dataset.csv
4920

4. Symptom-severity.csv
133


- Is there any missing data?

NA


- Does the dataset contain data that might be considered confidential (e.g., data that is protected by legal privilege or by doctor–patient confidentiality, data that includes the content of individuals’ non-public communications)?

1. This dataset only contain information of diseases, type of symptoms, and the precaution that was given for the specific disease. Therefore there are no confidential data in this dataset.


## Collection process

- How was the data acquired? 

1. NA

- If the data is a sample of a larger subset, what was the sampling strategy? 

1. NA

- Over what time frame was the data collected?

1. NA

## Preprocessing/cleaning/labelling

- Was any preprocessing/cleaning/labeling of the data done (e.g., discretization or bucketing, tokenization, part-of-speech tagging, SIFT feature extraction, removal of instances, processing of missing values)? If so, please provide a description. If not, you may skip the remaining questions in this section. \

1. Some  processing are done to group the severity of the different type of symptoms
2. Each disease symptoms is rewritten and split in its simple form to promote normalisation in information.


- Was the “raw” data saved in addition to the preprocessed/cleaned/labeled data (e.g., to support unanticipated future uses)? 

1. 'Raw' data is not provided by the author of this dataset. 

## Uses

- What other tasks could the dataset be used for? 
1. Exploratory information of the most common type of precaution and symptoms of the different diseases


- Is there anything about the composition of the dataset or the way it was collected and preprocessed/cleaned/labeled that might impact future uses? For example, is there anything that a dataset consumer might need to know to avoid uses that could result in unfair treatment of individuals or groups (e.g., stereotyping, quality of service issues) or other risks or harms (e.g., legal risks, financial harms)? If so, please provide a description. Is there anything a dataset consumer could do to mitigate these risks or harms? 
1. This dataset only contains a list of 132 different unique symptoms and 40 different diseases only. Any thing out of this range of coverage should not be used.
2. This dataset only contain very simple type of precaution and should not be used as a true medical precautions

- Are there tasks for which the dataset should not be used? If so, please provide a description.
1. NA

## Distribution

- How has the dataset already been distributed? 

1. Distributed on [Kaggle](https://www.kaggle.com/datasets/itachi9604/disease-symptom-description-dataset?select=dataset.csv)

- Is it subject to any copyright or other intellectual property (IP) license, and/or under applicable terms of use (ToU)?  

1. Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)


## Maintenance

- Who maintains the dataset?

1. Pranay Patil (Owner)

