### Thyroid Disease prediction
In this project we use Machine Learning (ML) models to predict if a person has thyroid or not based on the data given.<br>
This project also has data visualization techniques.

### Dataset
The data used is available in kaggle: [Thyroid Dataset](https://www.kaggle.com/datasets/yasserhessein/thyroid-disease-data-set) <br>

### Packages used:
- scikit-learn
- pandas
- seaborn
- matplot-lib
- plotly
- imbalanced-learn

Execute this code in your terminal before you start jupyter notebook:
```bash
pip install -r requirements.txt
```
This above code install all the required packages to run the model
NOTE: This above code is required only if you are running in your computer not in colab

### Information about model:
In this model, I will predict two thyroid conditions and if a person have thyroid or not, and also predict the hyperthyroid condition. So this model is muliclass classification model.
Algorithms used:
1. Decision Trees
2. Logistic Regression
3. Random Forest
4. Support Vector Machine
5. Feed Forward (Multi layer perceptron)


### Results Achieved:
|Model|Accuracy|
|---|---|
|Decision Tree |99.37%|
|Logistic Regression| 91.47%|
|Random Forest |99.90%|
|SVM|94.94%|
|Feed Forward|98.50%|
