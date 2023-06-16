# loan-eligibilty-prediction
Import the necessary libraries: pandas, numpy, matplotlib, seaborn, and sklearn. Read the loan dataset from a CSV file using pandas. 
Perform exploratory data analysis (EDA) by visualizing the data using box plots and histograms.
Handle missing values by replacing them with appropriate values based on mode or mean. 
Create a new feature called "Totalincome" by summing up the "ApplicantIncome" and "CoapplicantIncome" columns. 
Normalize the "Totalincome" values by taking the logarithm. Extract the independent variables (features) and dependent variable (target) from the dataset.
Encode categorical variables using label encoding. 
Split the dataset into training and testing sets using train_test_split. 
Apply feature scaling using StandardScaler to standardize the feature values.
Build a decision tree classifier model using DecisionTreeClassifier.
Predict the loan eligibility for the test set. 
Calculate and print the accuracy of the decision tree classifier model.
Build a random forest classifier model using RandomForestClassifier. 
Create a confusion matrix to evaluate the performance of the random forest classifier model.
