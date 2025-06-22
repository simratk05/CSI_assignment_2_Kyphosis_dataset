# CSI_assignment_3_Kyphosis_dataset

**Project Overview** 

This project focuses on analyzing the Kyphosis dataset obtained from Kaggle ( https://www.kaggle.com/abbasit/kyphosis-dataset ). The dataset was cleaned , EDA was Done and used to train three machine learning models: Logistic Regression, Decision Tree, and Random Forest. The objective was to predict the presence of kyphosis based on various features and compare the performance of the models.

**Dataset**

The Kyphosis dataset contains information on patients who underwent spinal surgery. Key attributes in the dataset include:

1. Kyphosis: Indicates whether kyphosis is present after the operation (Yes/No).

2. Age: Age of the patient (in months).

3.Number: The number of vertebrae involved in the operation.

4. Start: The number of the first (topmost) vertebra operated on.

# Data Cleaning:

1.Handled missing values and ensured the data was in the correct format for model training.

![image](https://github.com/user-attachments/assets/a8005c4d-abb5-4060-89fc-0c97bdda7203)


2.Checked for outliers and inconsistencies.

![image](https://github.com/user-attachments/assets/92473616-54f7-4311-9650-d2c638fdd578)


3.Visualized relationships between features.

![image](https://github.com/user-attachments/assets/35e0a83b-16a2-47a1-a4d3-dc8ecd9c163f)


4.Analyzed the distribution of the target variable (Kyphosis).


# Model Training and Evaluation:

Three models were trained using the cleaned dataset:

![image](https://github.com/user-attachments/assets/f625a2a9-4ced-4b81-bc9b-cbe61b905d4c)


# Observations:

1.Logistic Regression performed the best with an accuracy of 84%.

2.Random Forest achieved a decent accuracy of 80%, benefiting from its ensemble approach.

4.The Decision Tree model underperformed with an accuracy of 64%, likely due to overfitting.
