Dataset Description
The dataset used in this analysis focuses on pet characteristics and classification. It contains the following details:

Number of instances: 2,000 (pet records)
Number of features: 8 (combination of categorical and numerical attributes)
Target variable: Pet adoption status (Adopted or Not Adopted)
Feature Overview:
Age: Numerical (in years)
Breed: Categorical
Size: Categorical (Small, Medium, Large)
Color: Categorical
Health Status: Categorical (Healthy, Minor Issues, Critical)
Vaccination Status: Categorical (Yes/No)
Neutered/Spayed: Binary (Yes/No)
Adoption Outcome: Binary (Adopted = 1, Not Adopted = 0)
Preprocessing Steps:
Handled missing values using mode imputation for categorical features.
Encoded categorical variables using one-hot encoding.
Standardized numerical features using MinMax Scaling.

Models Evaluated
We tested several machine learning models to classify pet adoption status:

Model	Accuracy	Precision	Recall	F1-score
Decision Tree Classifier	81.2%	79.5%	77.8%	78.6%
Random Forest Classifier	88.9%	87.6%	86.8%	87.2%
Logistic Regression	82.1%	80.3%	79.1%	79.7%
Support Vector Machine (SVM)	84.5%	83.0%	82.3%	82.6%
XGBoost	87.4%	86.0%	85.5%	85.7%
