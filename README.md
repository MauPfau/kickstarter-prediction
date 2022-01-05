# kickstarter_prediction


Project to test different predictive algorithms to find if a Kickstarter project will succeed


## _Description_
The idea behind this project is to use different predictive algorithms, and compare the results.
The dataset we use is found on Kaggle.
We try to predict if a Kickstarter project will succeed or fail to reach its goal in the given time.
We build a usable dataset by taking into account different features that might impact the result (category, number of days, number of projects the same day, ...)
We use different algorithms (SVM, Random Forest, Neural Network, ...)

### _Structure_
- **Final_Report.pdf** : main report file, with results and method
- **base_creation_main_results.ipynb** : main notebook, with base creation, best model results for each type of model
- **inflation.csv** : file used in base creation to adjust prices to inflation
- **ks-projects-201801.csv** : base data file with projects from previous years from the crowdfunding Kickstarter website
