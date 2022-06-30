# diamond-valuation
The machine learning model in this reposotory deals with evaluating the price of a diamond based on its features like type of cut, its size, colour etc. The dataset used is present in the repository. The dataset contains 50,000+ rows of data.
The model first does preprocessing of dataset. Then it does feature selection using various techniques like Variance Threshold technique and Pearson correlation method. Then various models like linear regression, decision tree, SVM, random forest and XGBoost are trained on training data by creating a pipeline.
The result concludes that XGBoost performs the best on test set with an MSE score of just $489.5 and test accuracy of about 98%.
