# Kaggle Titanic - Machine Learning from Disaster Competition

## Introduction
[Titanic - Machine Learning from Disaster](https://www.kaggle.com/c/titanic) is one of the machice learning competitions on Kaggle. In general, the Kaggle's machice learning competitions are a fun, structured way to practice applying skills to real-world problems. Hence, this notebook was used for the Titanic competition to develop a machine learning model that predicts who survived the sinking of the Titanic.


**Data Dictionary:**
* `Survived` is the survival of Titanic passengers.
  * 0 = Not Survived
  * 1 = Survived
* `Pclass` is ticket class.
  * 1 = 1st Class
  * 2 = 2nd Class
  * 3 = 3rd Class
* `Sex` is gender of Titanic passengers.
* `Age` is the age in years
* `SibSp` is the number of siblings / spouses aboard the Titanic.
* `Parch` is the number of parents / children aboard the Titanic.
* `Ticket` is the ticket number.
* `Fare` is the passenger fare.
* `Cabin` is the cabin number.
* `Embarked` is the port of Embarkation.
  * C = Cherbourg
  * Q = Queenstown
  * S = Southampton


### Python Libraries
pandas, numpy, seaborn, matplotlib, scikit-learn, tensorflow


Read the complete project [here](https://www.kaggle.com/code/seuwenfei/titanic-random-forest-cv-score-0-85#2.1-Missing-Values).

## Conclusion
A Random Forest Classification with a cross validation score of 0.85 was obtained.
