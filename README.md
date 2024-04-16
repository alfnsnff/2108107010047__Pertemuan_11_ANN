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

## Compare
### Classification
#### ANN
    -  9/9 ━━━━━━━━━━━━━━━━━━━━ 0s 2ms/step - accuracy: 0.9306 - loss: 0.4001 
    -  Accuracy: 0.9090909090909091
#### SVM
    -  Akurasi: 0.8518518518518519

### Regression
#### ANN
    - Root Mean Square Error (RMSE): 1.7911436158306753
    - Mean Absolute Error (MAE): 1.087879800796509
    - R-squared (R^2): 0.8980536332952823
#### SVM
    - Mean Absolute Error: 2.435113377092408
    - Mean Squared Error: 10.506363752657839
    - Root Mean Squared Error: 3.241352148819662



## View Notebooks:
### Vew from github
Simply click or choose one of listed notebooks above to view the notebook
### Locally
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