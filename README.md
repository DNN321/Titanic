1. Problem Definition
“what sorts of people were more likely to survive the sinking of the Titanic?” using passenger data (ie: name, age, gender, socio-economic class, etc)

2. Data
https://www.kaggle.com/competitions/titanic/data we have train.csv and test.csv In this competition, you’ll gain access to two similar datasets that include passenger information like name, age, gender, socio-economic class, etc. One dataset is titled train.csv and the other is titled test.csv.

Train.csv will contain the details of a subset of the passengers on board (891 to be exact) and importantly, will reveal whether they survived or not, also known as the “ground truth”.

The test.csv dataset contains similar information but does not disclose the “ground truth” for each passenger. It’s your job to predict these outcomes.

Using the patterns you find in the train.csv data, predict whether the other 418 passengers on board (found in test.csv) survived.

Check out the “Data” tab to explore the datasets even further. Once you feel you’ve created a competitive model, submit it to Kaggle to see where your model stands on our leaderboard against other Kagglers.

3. Evaluation
Evaluation metric to use: Accuracy, Precision, Recall, f1_score, ROC and AUC curve

4. Features
we have structured data with train.csv with a total of 891 passengers of features and labels with test.csv with a total of 418 passengers submission file to have one feature : PassengerId and one label : Survived

5. Modelling
models to use: 1. Linear SVC 2. KNeighborsClassifier 3. RandomForestClassifier
