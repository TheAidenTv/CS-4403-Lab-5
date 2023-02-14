# CS-4403-Lab-5

## The Task

[Here](https://github.com/TheAidenTv/CS-4403-Lab-5/files/10736061/diabetes.csv) is a dataset of medical data (features) with respect to a group of female indigenous Pima, which are labelled to indicate whether the particular individual represented by a row in the dataset developed diabetes within 5 years or not.  This is a classic classification example used in many courses to illustrate the classification machine learning process and to practice with.

The features tracked in the dataset are (in order):
1. Number of times pregnant.
2. Plasma glucose concentration in an oral glucose tolerance test. A measure of blood sugar.
3. Diastolic blood pressure (mm Hg). Generally, and to a point, the lower the better.
4. Triceps skinfold thickness (mm). A measure of how much bodyfat the individual has.
5. 2-Hour serum insulin (mu U/ml). A measure of insulin production.
6. Body mass index (weight in kg/(height in m)^2). A metric to measure body fat ration.
7. Diabetes pedigree function. An indication of historic propensity to develop diabetes. A higher number suggests stronger history.
8. Age (years).
9. Class variable (0 or 1), whether the individual developed diabetes within 5 years or not.

The data is already cleaned and there are no null values, etc.  You should be able to feed the features directly into a machine learning algorithm.

Using the template for building a train/test classification model we walked through in class, build a classification model using this feature set, and report your Accuracy scores and Classification Report.

Be aware that it is difficult to get really high scores for this dataset, but give it a go and let's see how you do!

Try some different combinations of features and some different algorithms to see if you can improve your score.  Try doing a correlation matrix to see if that helps
