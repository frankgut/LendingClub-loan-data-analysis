# LendingClub Loan Data Analysis

**Make sure you check out the fully rendered jupyter notebook with all the outputs and interactive plots. Use the link below. Notebook itself without outputs can be found within this repository.**

[Fully rendered notebook](https://nbviewer.jupyter.org/github/frankgut/LendingClub-loan-data-analysis/blob/master/Lending-club-loan-data-analysis.html)

In this project, I used publicly available data (2007-2011) from the LendingClub.com. I explored the dataset and created models to classify whether a profile would have a high probability of paying back a loan or not.


- Visualize the dataset to help understand the features that could affect a borrower's loan status
- Prepare the data by cleanning, handeling missing data, feature selection and converting categorical features etc.
- Address a possible data leakage problem within the dataset and its impact on the feature selection process
- Build models of Ensemble (AdaBoost, GradientBoosting, ExtraTrees, RandomForest), Logistic Regression, Naive Bayes, K Nearest Neighbors, Support Vector Machine, Decision Tree and Multilayer Perceptron to predict whether a borrower would pay back a loan or not
- Tune the hyperparameters for a set of selected models based on their cross-validation scores
- Use learning curve to test whether a certain model overfits the data and rank feature importance for several tree-based models
- Evaluate the model accuracy based on their scores on the test dataset and compare them with the baseline accuracy
