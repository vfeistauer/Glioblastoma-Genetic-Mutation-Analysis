# :brain: Glioblastoma Genetic Mutation Analysis :dna:


**--> PROJECT UNDER DEVELOPMENT**

Gliomas are central nervous system tumors that originate from glial cells, the supportive cells responsible for maintaining and protecting neurons. LGG (Lower-Grade Glioma) and GBM (Glioblastoma Multiforme) are distinct grades of gliomas, representing different levels of malignancy in brain tumors. LGGs, classified as WHO grades I and II, exhibit less cellular atypia and slower growth compared to GBMs. LGGs are generally considered less aggressive, with a more favorable prognosis and longer overall survival rates. Treatment approaches for LGGs involve surgery, radiation therapy, and chemotherapy. In contrast, GBMs, categorized as WHO grade IV, are highly aggressive tumors characterized by rapid growth, extensive invasion into surrounding brain tissue, and a poor prognosis. GBMs require more intensive treatment, including surgery, radiation therapy, and targeted chemotherapy. Differentiating between LGG and GBM is crucial for determining appropriate treatment strategies and predicting patient outcomes.

**_Main Objective:_**
The main objective of the analysis is to develop a predictive model to determine the glioma grade (LGG or GBM) using a combination of clinical and molecular/mutation features. The aim is to identify the optimal subset of mutation genes and clinical features that can accurately predict the glioma grade, resulting in a more precise and agile diagnosis.

**_Specific Objectives:_**

- Exploratory Data Analysis: Conduct exploratory data analysis to gain insights into the distribution and characteristics of the clinical and molecular features, as well as their relationship with the glioma grade.
- Feature Selection: Apply feature selection techniques to identify the subset of molecular genes and clinical features that have the most significant impact on predicting the glioma grade. Evaluate the importance of each feature using appropriate methods such as feature importance scores or statistical tests.
- Model Development: Develop a predictive model using the selected features to classify gliomas as LGG or GBM. Optimize the model parameters and hyperparameters to achieve the best performance. The models tested in the dataset will be: Support Vector Classifier, Decision Trees and Random Forest.
- Model Evaluation: The models will be evalueted using appropriate metrics such as accuracy, precision, recall and F1-score. Assess the model's ability to accurately predict the glioma grade and its generalization to new, unseen data.
- Hyperparameter Tuning:  After selecting the best performing model, based on the evaluation metrics cited above, we will further enhance its performance through hyperparameter tuning by systematically adjusting the model's hyperparameters. The objective is to find the optimal configuration that maximizes the model's predictive capabilities. This process will be conducted using grid search, where different combinations of hyperparameters will be evaluated and compared to identify the best set of hyperparameter values for our model. By fine-tuning the hyperparameters, we aim to improve the model's generalization ability and enhance its overall performance.
- Interpretation and Insights: Interpret the results of the analysis, providing insights into the importance of specific molecular genes and clinical features in predicting the glioma grade. Investigate any associations or correlations between these features and the glioma grade, providing potential biological or clinical implications.
