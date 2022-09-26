# Titanic Survival Prediction

In this project, we use the Titanic dataset from Kaggle to predict whether a passenger survived or not. The dataset has the following features:

* **'Survival'** :	Survival	0 = No, 1 = Yes
* **'Pclass'** : Ticket class
* **'Sex'** :	Sex	
* **'Age'** :	Age in years	
* **'Sibsp'** :	# of siblings / spouses aboard the Titanic	
* **'Parch'** :	# of parents / children aboard the Titanic	
* **'Ticket'** :	Ticket number	
* **'Fare'** :	Passenger fare	
* **'Cabin'** :	Cabin number	
* **'Embarked'** :	Port of Embarkation
* **'Name'** : Name of the passenger

Two more features were added - **'Title'** (based on **'Name'**) and **'IsAlone'** (based on **'Sibsp'** and **'Parch'**)

The prediction was done using Logistic Regression and it had a weighted avg F1 score of 0.82
