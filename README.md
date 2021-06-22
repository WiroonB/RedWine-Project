## Wine Project(Python)

Data science project completed using Pandas, Seaborn, Matplotlib as well as SKLearn to create different models and predict.

### Overview

**Problem Statement**

Given data of red wines which contains differrent chemical measurements of wine ( Fixed acidity, Volatile acidity, Citric acid,  Residual sugar, Free sulfur dioxide, Total sulfur dioxide, Density, pH, Sulphates, Alcohol, and  quality rating from 1 to 8. Can we predict whether a wine is a good or bad wine. 

**Approach**

I started with with preprocessing data before predicting the target variable which is Wine quality and spliting the data into training and testing groups. Then I implemented two diffrent algorithms, which are Random Forest Classifier and Support Vector Machine (SVM) Classifier to model and fit the data. In addition, I also optimized SVM Classifier with Hyper-parameter using GridSearch (GridSearchCV()). To quantify the models, I used the metrics of model accuracy, model classification report (F1 Score, Precision, Accuracy Between Classes, Recall), model confusion matrix and AUC(Area Under the Curve) which is a better measure for accuracy of a binary classification problem.

**Result**

In this notebook, I implemented Random Forest, SVM and SVM with Hyper-parameter tuning. 
Random Forest : AUC Score: 0.55, Model Accuracy Score 86.88% : , F1 Score : 0.58
SVM           : AUC Score: 0.62, Model Accuracy Score 87.50% : , F1 Score : 0.65
SVM GridSearch: AUC Score: 0.65, Model Accuracy Score 89.06% : , F1 Score : 0.69

| | | 
|:-------------------------:|:-------------------------:|
|<img width="1604" alt="screen shot 2017-08-07 at 12 18 15 pm" src="https://github.com/WiroonB/Wine-Project-Python/blob/main/Images/RandomForest.png?raw=true"> Random Forest |  <img width="1604" alt="screen shot 2017-08-07 at 12 18 15 pm" src="https://github.com/WiroonB/Wine-Project-Python/blob/main/Images/ConfusionMatrix.png?raw=true"> Confusion Matrix ||



### Note

Because this dataset is imbalanced, AUC is a better measure for accuracy of a binary classification problem which is why it is included in model performance.
F1 score is also a better metric to evaluate the models.


