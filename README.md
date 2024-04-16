# Machine Learning Assigment 3
## Classification and Regression with ANN

M. Alfan Septian Nufi - 2108107010047

Datasets: 
-   Classification : https://www.kaggle.com/datasets/sujithmandala/obesity-classification-dataset
-   Regression : https://www.kaggle.com/datasets/tawfikelmetwally/advertising-dataset

About datasets:
-   Classfication dataset contains information about the obesity classification of individuals. The data was collected from a variety of sources, including medical records, surveys, and self-reported data. The dataset includes the following columns:
    -  ID: A unique identifier for each individual
    -  Age: The age of the individual
    -  Gender: The gender of the individual
    -  Height: The height of the individual in centimeters
    -  Weight: The weight of the individual in kilograms
    -  BMI: The body mass index of the individual, calculated as weight divided by height squared
    -  Label: The obesity classification of the individual, which can be one of the following: [Normal, Weight, Overweight, Obese, Underweight]
-   Regression dataset expresses sales according to the type of advertisement and the size of the cost .
The dataset contains 200 rows of 3 features [ TV , Radio , Newspaper] and target variable [Sales]

Notebooks: 
- [ANN Classification](ANN_Classification.ipynb) 
- [ANN Regression](ANN_Regression.ipynb)

# Comparison

## Classification
Artificial Network:
    -  Accuracy: 0.9090909090909091

Support Vector Machine:
    -  Akurasi: 0.8518518518518519

## Regression
Artificial Network:
    - Root Mean Square Error (RMSE): 1.7911436158306753
    - Mean Absolute Error (MAE): 1.087879800796509
    - R-squared (R^2): 0.8980536332952823

Support Vector Machine:
    - Mean Absolute Error: 2.435113377092408
    - Mean Squared Error: 10.506363752657839
    - Root Mean Squared Error: 3.241352148819662

Based on the provided comparison between Artificial Neural Network (ANN) and Support Vector Machine (SVM) models for both  classification and regression tasks, here are the conclusions:

    - Classification:
        - ANN achieved a higher accuracy of 0.909 compared to SVM with an accuracy of 0.852. This indicates that ANN performed better in classifying the data into different categories.
    - Regression:
        - ANN outperformed SVM in terms of regression performance metrics:
        - ANN had lower Root Mean Square Error (RMSE) of 1.791 compared to SVM's Root Mean Squared Error of 3.241. Lower RMSE indicates that the ANN model's predictions were closer to the actual values compared to SVM.
        - ANN also had lower Mean Absolute Error (MAE) of 1.088 compared to SVM's Mean Absolute Error of 2.435. Lower MAE indicates that the ANN model's predictions had smaller average errors compared to SVM.
        - ANN achieved a higher R-squared (R^2) value of 0.898 compared to SVM's R-squared value, which indicates that the ANN model explained more of the variance in the target variable compared to SVM.
        - Overall Conclusion:
        - For both classification and regression tasks, the Artificial Neural Network (ANN) model outperformed the Support Vector Machine (SVM) model.
        - ANN showed higher accuracy in classification and better performance metrics (lower RMSE, lower MAE, and higher R^2) in regression compared to SVM.
        Therefore, ANN appears to be the better choice for both classification and regression tasks based on the provided comparison.


## How to view Notebooks:
Simply [download](https://github.com/alfnsnff/Tugas2ML/archive/refs/heads/master.zip) or clone the repository that already include the datasets and run the notebooks locally

[IMPORTANT] Some Requirements is Needed. Use Virtual Environment by Create Ur Own Virtual Environments Following These Steps
 
Note: This following code is used for windows
Create Virtual Environment
```
python -m venv venv
```
Install Following Requirements
```
pip install -r requirements.txt
```
Activate Virtual Environment
```
venv\Scripts\activate
```
OPTIONAL: Deactivate
```
deactivate
```