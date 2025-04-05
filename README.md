Complete the tasks using the package scikit-learn (classifiers from libraries).

Create a dataset using: make_moons(n_samples = 10000, noise = 0.4). Visualise it. 

Split the dataset into training and test subsets using the train_test_split() method. (1p)

Use a tree as a classifier (DecisionTreeClassifier). Investigate the operation of the tree for entropy and Gini coefficient and different depths of the tree. Visualise 3 chosen trees using the method plot_tree from the library “tree”. (3p)

Use random forests as the classifier (RandomForestClassifier). Test the performance of the classifier for a different number of decision trees. Visualise at least 1 tree from 3 chosen random forests. (3p)

Train Logistic Regression Classifier (LogisticRegression) and SVM. Visualise them using for example the function from the file plotka.py shared on FTP or plot_decision_regions from the library “mlxtend”. (1p)

Combine the SVM, LogisticRegression and RandomForestClassifier classifiers into one group (VotingClassifier) to improve the classification. (1p)

Sum up the results achieved. (1p)
