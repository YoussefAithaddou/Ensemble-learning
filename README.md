# Ensemble-learning

This mini-project is an application and comparaison between Ensemble-learning methods. 

* Uploaded and cleaned Covid-19 Data.
* Built initial RNN model (2 LSTMs of 64 units) to forecast the number of coronavirus cases, achieved MSE =  123.324.
* Performed model optimization with Tensorboard using 36 combination of LSTM and Dense layers.
* Built final model (1 LSTMs of 128 units, 1 Dropout (20%), 1 Flatten and 1 Dense layer) with MSE = 106.181 (Mean error reduction = 14 %).


# Resources Used
* Python Version: 3.7
* Packages and Libraries: pandas, matplotlib, sklearn.
# Data used
* Sklearn make_moons datset.

# Models adn Results:
* DecisionTreeClassifier: 0.94
* SGDClassifier: 0.872
* KNeighborsClassifier: 0.952
* VotingClassifier: 0.968
* BaggingClassifier: 0.972
* RandomForestClassifier: 0.964
* AdaBoostClassifier: 0.96
* GradientBoostingClassifier: 0.964
* StackingClassifier: 0.96
# Discussion:
In general, ensemble learning methods perform better than each indivual method ensembling it.
