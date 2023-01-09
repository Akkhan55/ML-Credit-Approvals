# ML-Credit-Approval
Using a collection of input data, this code aims to build a machine learning model that can forecast whether a credit card application will be granted or refused. A dataset containing the input data has several characteristics including the applicant's income, credit score, and number of credit cards. A subset of the data (the training set) is used to train the model, while a different portion of the data (the test set) is used to test the model's performance.

# About
The program first feeds the dataset into pandas, preprocesses it, and then divides it into training and test sets. Depending on the column's data type, the preprocessing procedures also involve removing certain columns, replacing "?" with NaN values, imputing missing values with the mean or the most common value, one-hot encoding categorical features, and scaling the features. Following preprocessing, the code creates predictions using the test data and fits a logistic regression model to the training data. The model's accuracy score and confusion matrix are then calculated, and GridSearchCV is used to figure out the best hyperparameter values.
