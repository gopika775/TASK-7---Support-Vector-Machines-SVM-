# TASK-7---Support-Vector-Machines-SVM-

Breast Cancer Classification Project


This project applies Support Vector Machines (SVM) to classify tumors as benign or malignant using the Breast Cancer Diagnostic dataset.

------------------------------------------------------------------------------------------------------------------------------------------------

Tasks Performed

- Loaded and explored the breast cancer dataset from CSV file (breast cancer data.csv)
- Checked for and handled missing values
- Dropped unnecessary columns like id and Unnamed: 32
- Encoded the target feature (diagnosis: M/B → 1/0)
- Split the dataset into training and testing sets
- Standardized the feature set using StandardScaler
- Trained two SVM models using:
  1. Linear kernel
  2. RBF (Radial Basis Function) kernel
- Evaluated model performance using:
  1. Confusion Matrix
  2. Accuracy Score
  3. Classification Report (Precision, Recall, F1-score)
- Tuned hyperparameters (C, gamma) using GridSearchCV
- Applied cross-validation to validate model performance
- Visualized the decision boundary in 2D using two selected features: radius_mean and texture_mean

--------------------------------------------------------------------------------------------------------------------------------------------------

Libraries Used

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn (sklearn)

---------------------------------------------------------------------------------------------------------------------------------------------------

Final Output

A trained and evaluated SVM classification model that distinguishes between malignant and benign tumors. The project includes:
- Comparison of linear and RBF kernels
- Performance metrics on test data
- Hyperparameter optimization using grid search
- Cross-validation scores
- 2D decision boundary visualization of RBF kernel using selected features

