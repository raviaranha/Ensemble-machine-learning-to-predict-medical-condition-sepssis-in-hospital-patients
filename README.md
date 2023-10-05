# Ensemble-machine-learning-to-predict-medical-condition-sepssis-in-hospital-patients

## Project Approach
- The project starts with importing relevant python packages required for the
analysis
- The training data for the analysis is imported next (The prediction data will be
imported post model training)
- The dataset characterestics are explored next, including shape, summary
statistics, data types, value and missing counts, distributions
- Next, we will execute any column transformations, as needed at this step
We will look at unqiue values in each columns
- Next, we will explore the data visually using histograms, scatterplots, box
plots and correlation plots
- We will also document the observations from the exploratory analysis
(and highlight variable interations to aid ML modeling)
- Next, we will split data into train-validation sets (to help understand
accuracy and enable hyperparameter tuning)
- We will also explore the similarities within the train-validation datasets
- Next, we will implement normalization the data to help ML models (We will
fit on train data, and transform train/validation/test datasets)
- We will set up a performance evaluation framework to analyze ML models
(We will primary look at the accuracy to finalize models, but will also explore
f1 scores as part of the process)
- Next, we will run multiple ML models
- This being a classification model, we will explore relevant ML models
such as Naive Bayes, Logistic Regression, Decision Trees & Random
Forest
- Baseline models as well as tuned varients (hyper-parameter tuning) will
be explored along with associated performance metrics
- Finally, a champion model will be chosen basis critical analysis and
predictions on test data will be made using the chosen model
