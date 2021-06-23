## Wine Project(Python)

Data science project completed using Pandas, Seaborn, Matplotlib as well as SKLearn to create different models and predict.

### Overview

**Problem Statement**

Given data of red wines which contains differrent chemical measurements of wine ( Fixed acidity, Volatile acidity, Citric acid,  Residual sugar, Free sulfur dioxide, Total sulfur dioxide, Density, pH, Sulphates, Alcohol, and  quality rating from 1 to 8. Can we predict whether a wine is a good or bad wine. 

**Approach**

I started with with preprocessing data before predicting the target variable which is Wine quality and spliting the data into training and testing groups. Then I implemented two diffrent algorithms, which are Random Forest Classifier and Support Vector Machine (SVM) Classifier to model and fit the data. In addition, I also optimized modles with Hyper-parameter using GridSearch and class weighting. To quantify the models, I used the metrics of model accuracy, model classification report (F1 Score, Precision, Accuracy Between Classes, Recall), model confusion matrix and AUC(Area Under the Curve.)

**Result**
| | | | |
| ----------- | ----------- | ----------- | ----------- |
| **Model** | **AUC Score** | **Accuracry Score** | **F1 Score** |
| Random Forest| 0.56 | 86.88% | 0.58 |
| Weighted Random Forest | 0.76 | 92.19% | 0.81 |
| SVM | 0.62 | 87.50% | 0.65 |
| Weighted SVM | 0.88 | 84.07% | 0.77 |
| Weighted SVM GridSearch | 0.76 | 90.63% | 0.79 |

| | | 
|:-------------------------:|:-------------------------:|
|<img width="1604" alt="screen shot 2017-08-07 at 12 18 15 pm" src="https://github.com/WiroonB/Wine-Project-Python/blob/main/Images/RandomForest.png?raw=true"> Random Forest |  <img width="1604" alt="screen shot 2017-08-07 at 12 18 15 pm" src="https://github.com/WiroonB/Wine-Project-Python/blob/main/Images/ConfusionMatrix.png?raw=true"> Confusion Matrix ||



### Note

Because this dataset is imbalanced, AUC is a better measure for accuracy of a binary classification problem which is why it is included in model performance.
F1 score is also a better metric to evaluate the models.


