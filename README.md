Problem Statement -
https://www.kaggle.com/competitions/santander-customer-satisfaction/overview

To-Do List:

(1) Since the genetic algorithm (GA) will solve many classification problems, use a smaller training set for feature selection and hyperparameter tuning. For example, use all the minority class data points (about 3000) and then gradually increase the number of majority class data points, starting at 3000. You should get a sense of the good features and hyperparameters by quickly trying out a few different datasets (e.g. increase the majority class size in increments of 3000). For each algorithm (e.g. random forest, gradient boosting), first, do feature selection with GA, then hyperparameter tuning with GA using the selected features.

(2) Santander has 370 features. Use the genetic algorithm (GA) to get the top 25 and top 50 features using two different classification algorithms (e.g. random forest and gradient boosting). Compare their top features with SelectKBest top 25 and top 50 features. How many of the features are common between them?

(3) Use the genetic algorithm (GA) for hyperparameter tuning and build four classification models - if you use random forest and gradient boosting as classifiers, then construct two models for each classifier, one with the top 25 features and the other with the top 50 features. To construct these classifiers, you can combine the common features across all the methods used in step 2 to get your top 25 and top 50 features. You can also use a smaller training set for hyperparameter tuning as outlined in step 1.

(4) Build final classification models (four of them - two each for the top 25 and top 50 features) with the best parameters found in step 3. In this step, you can use all of the training data.

(5) Do Kaggle submissions for all four models and record all Kaggle scores/rankings in your report.
