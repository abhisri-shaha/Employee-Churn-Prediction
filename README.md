
# Employee Churn Prediction

Machine learning models to forecast employee churn at Salifort Motors. By analyzing key factors such as tenure, project involvement, and average monthly working hours, the model will identify employees at risk of leaving the company. The insights gained will inform targeted retention strategies to enhance workforce stability and reduce turnover.


## Background
Salifort Motors is a fictional French-based alternative energy vehicle manufacturer. Its global workforce of over 100,000 employees research, design, construct, validate, and distribute electric, solar, algae, and hydrogen-based vehicles. Salifort’s end-to-end vertical integration model has made it a global leader at the intersection of alternative energy and automobiles. 

As a data specialist working for Salifort Motors, you have received the results of a recent employee survey. The senior leadership team has tasked you with analyzing the data to come up with ideas for how to increase employee retention. To help with this, they would like you to design a model that predicts whether an employee will leave the company based on their  department, number of projects, average monthly hours, and any other data points you deem helpful. 


## EDA (Exploratory Data Analysis)
### Data exploration
- **Dataset**: The dataset is fictional. It includes employee information such as satisfaction level, last performance review, number of projects, average monthy hours, tenure, department, salary, etc.
- **Size**: There are 14999 entries in the dataset.
- **Basic information**: Number of non-null entries in each column and their respective datatypes.
- **Descriptive statistics**: Key metrics such as mean, standard deviation, minimum, maximum, etc.

### Data cleaning 
- **Missing values and duplicates**: Check and handle missing values and duplicates in the dataset. 
- **Outlier Removal**: Identify and remove outliers from tenure.

### Data visualization
- **Box Plots**: Examine the spread of values in various columns
- **Histograms**: Explore the distribution of variables
- **Scatter Plots**: Explore correlations between different features
- **Heatmap**: Visualize correlation between all pairs of variables


## Models and Evaluation Metrics

### Binary Logistic Regression
- **Objective**: Predicts employee churn
- **Results**:
  - **Accuracy**: 82%
  - **Precision**: 79% (weighted average)
  - **Recall**: 82% (weighted average)
  - **F1 score**: 80% (weighted average)
- **Interpretation**: Indicates good performance; further tuning needed.

### Decision Tree
- **Objective**: Predict employee churn
- **Results**:
  - **Accuracy**: 97.1%
  - **Precision**: 91.4% (weighted average)
  - **Recall**: 91.6% (weighted average)
  - **F1 score**: 91.5% (weighted average)
  - **AUC**: 96.9%
- **Interpretation**: Excellent performance; may indicate overfitting.


## Future Work
- **Integrate Ensemble Methods**: Explore ensemble techniques like Random Forest, Gradient Boosting, or XGBoost to improve prediction accuracy and model robustness.

## Conclusion
The models and the feature importances extracted from the models confirm that employees at the company are overworked, highlighting the need for improved workload management to enhance retention.
