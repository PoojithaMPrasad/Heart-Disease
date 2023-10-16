# Heart Disease Prediction Using Machine Learning Algorithms

## Description - 

       Healthcare today faces the challenge of providing practical, accurate diagnoses and high-quality services. In recent years, heart diseases have ranked as the leading cause of death worldwide, but they can also be controlled and managed effectively. An illness can only be managed accurately when detected at the right time. Recognizing heart disease at the onset phase is crucial to avoid disastrous consequences. Analyzing large amounts of data and predicting heart diseases is assisted by several Data Mining and ML tools. An analysis of Logistic Regression, Nave Bayes, Support Vector Machines, K-Nearest Neighbors, Decision Trees, Random Forests, and the ensemble Method of XGBoost is presented here to compare the most efficient approaches.

## Motivation - 

     For many types of data science applications, machine learning techniques have been compared and used. This research-based project was primarily motivated by a desire to explore the selection of features, data preparation, and processing behind machine learning models. Although I have first-hand knowledge of models and libraries, the biggest challenge I face today is data. The accuracy I see during training, testing, and validation in the cooked models has a high variance. Thus, this project aimed to explore and implement a Logistic Regression model to train the obtained data. Furthermore, since machine learning is motivated to develop a computer-based system and decision support for the early detection of heart disease, in this project, I am developing a model that predicts if a patient will grow heart disease in ten years or not based on various features (i.e., potential risk factors causing heart disease) by using logistic regression. Thus, early diagnosis of cardiovascular diseases can aid in making choices about lifestyle changes for high-risk patients, which can reduce complications, a significant advancement in medicine.


## Dataset -

    The dataset used in this research is the Heart Disease dataset from Kaggle. It comprises 14 attributes, such as age, sex, cholesterol levels, blood pressure, and other medical characteristics. This dataset is suitable for this research because it contains enough data points to train and test the machine learning model.

## Tools and Software - 

In this project, I have used the following tools and software. 
a)	Programming Languages: Python.
b)	Machine Learning Libraries: Scikit-learn, TensorFlow, Keras
c)	Storage: Pandas
d)	Data Visualization Tools: Matplotlib
e)	Web frameworks: Jupiter Notebook

## Algorithms Used - 

a) Support Vector Machine
b) Naïve Bayes
c) Decision Tree
d) Random Forest
e) Logistic Regression
f) Adaboost
g) XGBoost

## Data Preparation

Graph Before And After Dropping the Values
![Data Preparation](https://github.com/PoojithaMPrasad/Heart-Disease/assets/129121710/7dce0454-d97e-4f6c-9863-35ec06ae8e21)

Dataset after Scaling and Imputing
![Data Preparation 1](https://github.com/PoojithaMPrasad/Heart-Disease/assets/129121710/d5aabd19-c1d9-4f46-a73a-6ddd6ecf068d)

## Exploratory Analysis

Before Feature Selection, the correlation matrix is visualized.
![Exploratory analysis](https://github.com/PoojithaMPrasad/Heart-Disease/assets/129121710/de1c8544-9b70-4254-85e7-011559d45dbb)

## Feature Selection 

### P_Value
![P Value](https://github.com/PoojithaMPrasad/Heart-Disease/assets/129121710/8dfdae7d-4982-49b7-8321-cbaf57f08fb4)

![P Value 1](https://github.com/PoojithaMPrasad/Heart-Disease/assets/129121710/cb7ce0a6-82f2-4091-a232-bf5b2cd046f0)

### Cross Validation

![Cross Validation](https://github.com/PoojithaMPrasad/Heart-Disease/assets/129121710/74df73ac-6f8a-4d88-925b-5a0fd555f7b0)

## Training and Testing 
It was then necessary to divide the resulting data into 80% train data and 20% test data which was subsequently passed to the LogisticRegression model for the purpose of fitting, predicting and scoring the model.

## Result 
![Results](https://github.com/PoojithaMPrasad/Heart-Disease/assets/129121710/c8c1470f-0f59-4301-8ae8-3a5cf1985874)

![Results !](https://github.com/PoojithaMPrasad/Heart-Disease/assets/129121710/5f607805-b8be-44da-aebf-644ba17fe892)


