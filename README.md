# VPN-Non_VPN Network Traffic Classification using Machine Learning
## Dataset Description:
* Utilized the ISCX VPN non-VPN 2016 publicly available dataset, Each data point represents network flow from source to destination.
* Dataset was consisting 84 features.
## Data Preprocessing:
* Conducted an analysis of the dataset, examine its shape, identifies missing values, detecting duplicate values.
* Performed data cleaning to handle missing values and duplicate values.
* To remove dimensionality, select relevent features, employed the Pearson Correlation method.
* To ensure the unifrom scaling across features, applide in-max normalization technique.
## Model Building
* Built four different type of machine learning models.
* Evalauate the performances using appropriate metrics.
## Results

| Algorithm | Accuracy(%) |
| --------- | --------- |
| Decision Tree | 97 |
| Naive Bayes | 66 |
| Random Forest | 97 |
| Adaboost | 93 |
