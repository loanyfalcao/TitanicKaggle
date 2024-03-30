# TitanicKaggle
#### One of the most famous challenges on kaggle

Initially, data preprocessing was performed:

- A new feature, family size, was created by adding the number of companions to one;
- Zero fare values were filled with the mean fare paid by the class;
- The embarkation gate was filled according to the class;
- Titles that remained in the file were "Mr, Miss, Mrs, Master";

Following data preprocessing, machine learning models were built, including:
- Random Forest
- Logistic Regression
- K-Nearest Neighbours
- Gaussian Naive Bayes
- Linear Support Vector Machines
- Stochastic Gradient Descent
- Decision Tree Classifier
- Gradient Boost Trees

Given that Gradient Boost Trees exhibited the highest cross-validated accuracy, it was selected as the final model.
