# Kaggle_Titanic_Machine_Learning_from_Disaster
 Code of my submission in the Titanic compettion from Kaggle
 In this Kaggle compitition I tried to get the test accuracy close to cross validation accuracy. To do that, data preprocessing needto done. In here, first train test dataset was concateneted and then title was extracted from Name column and group them by 6 categories and create an new column Title to store them. Same thing was done with embarked, Fare. Ticket and passangerID was dropped. Sib and Parch were sum up to know the family_size,it'll help to know if survivor were from big family or not. Pclass, Sex and Title were group by and then there median was calculated to fillup the null Age. Finally after creating and dropping columns new table was form. So categorical values needed to turn into numerical values and then created MinMax scaler. After that differetn model and hyperparamter tuning was done to get around 80% accuracy. At the end Random Forest with GridSearchCV achived 79.185% test accuracy which was 7% position in kaggle leaderboad.
