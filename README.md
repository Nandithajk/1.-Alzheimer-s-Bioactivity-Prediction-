# 1.-Alzheimer-s-Bioactivity-Prediction-
## Machine Learning | Bioinformatics | Gammasecreatse complex protein

## Introduction
- Alzheimer's disease is a progressive neurological disorder that leads to memory loss, cognitive decline, and ultimately, the inability to carry out daily activities. It is the most common cause of dementia, affecting millions of people worldwide, particularly the elderly.
- Despite extensive research, there is currently no cure for Alzheimer's disease, and existing treatments only offer limited symptomatic relief.
- Identifying specific proteins involved in the pathogenesis of Alzheimer's disease is crucial for developing targeted therapies.
- Gamma-secretase, for instance, is a complex protein that plays a key role in the formation of amyloid-beta plaques, a hallmark of Alzheimer's pathology.
- Traditional drug discovery methods are time-consuming and costly, often taking over a decade and billions of dollars to bring a new drug to market.
- Computational drug discovery leverages advanced algorithms, machine learning models, and vast biological databases to predict the bioactivity of compounds efficiently.These methods can rapidly screen large libraries of compounds, identify potential drug candidates, and prioritize them for experimental validation.

### Data Acquisition: 
Extracted bioactivity data from the ChEMBL database, applied Lipinski's rule for descriptor-based feature extraction, and transformed IC50 values into pIC50 for target modeling.
### Data Pre-processing: 
Addressed missing values and conducted exploratory data analysis (EDA) through Chemical Space Analysis and Statistical Analysis using the Mann-Whitney U-test.
### Feature Engineering: 
Performed dataset preparation using fingerprint descriptors, implemented feature selection, scaling, and re-sampling techniques.
### Modelling: 
Developed and evaluated multiple supervised learning algorithms, including Linear Regression, Decision Tree, Random Forest, K-Nearest Neighbors (KNN), and Support Vector Machine (SVM).
##### Successfully deployed the SVM model, achieving 60% accuracy in predicting pIC50, via a web application using Streamlit.
 
