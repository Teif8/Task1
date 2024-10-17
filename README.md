# Data-preprocessing-task 

This repository contains a Jupyter Notebook demonstrating the following preprocessing techniques:
- Handling missing values.
- Encoding categorical columns.
- Scaling numerical data.

## Code Overview

1. **Initial Data**: We start with a sample dataset that includes missing values and categorical data.
2. **Missing Values**: 
   - Rows with missing data are removed.
   - Missing values in numerical columns (`Age`, `Salary`) are filled with the mean.
3. **Encoding**: Categorical columns (`Country`, `Purchased`) are encoded into numerical values using Label Encoding.
4. **Scaling**: Numerical columns (`Age`, `Salary`) are scaled using StandardScaler from scikit-learn.

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/data-preprocessing-task.git

2.	Install the required dependencies:
```
pip install pandas numpy scikit-learn
```
3.	Open the notebook data_preprocessing_task.ipynb and run the cells to see the preprocessing steps in action.

Dependencies

	•	Python 3.x
	•	Pandas
	•	Numpy
	•	scikit-learn
