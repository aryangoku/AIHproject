# AIH Project

## Overview
This project is implemented using Jupyter Notebook and focuses on AI-driven data analysis and model training for diabetes prediction. The notebook processes a dataset, performs exploratory data analysis, applies machine learning models, and evaluates their performance.

## Requirements
To run this project, ensure you have the following dependencies installed:
- Python 3.x
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

Install required libraries using:
```sh
pip install -r requirements.txt
```

## Installation
1. Clone this repository:
   ```sh
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```sh
   cd AIHproject
   ```
3. Launch Jupyter Notebook:
   ```sh
   jupyter notebook
   ```
4. Open `AIHproject.ipynb` and run the cells sequentially.

## Usage
- Run the notebook cells to load and preprocess the dataset.
- Perform exploratory data analysis (EDA) through generated visualizations.
- Train and evaluate machine learning models for diabetes prediction.
- Adjust hyperparameters and re-run models to improve performance.

## Results
- **Dataset Overview:**
  ```
  <class 'pandas.core.frame.DataFrame'>
  RangeIndex: 768 entries, 0 to 767
  Data columns (total 9 columns):
   #   Column                    Non-Null Count  Dtype  
  ---  ------                    --------------  -----  
   0   Pregnancies               768 non-null    int64  
   1   Glucose                   768 non-null    int64  
   2   BloodPressure             768 non-null    int64  
   3   SkinThickness             768 non-null    int64  
   4   Insulin                   768 non-null    int64  
   5   BMI                       768 non-null    float64
   6   DiabetesPedigreeFunction  768 non-null    float64
   7   Age                       768 non-null    int64  
   8   Outcome                   768 non-null    int64  
  dtypes: float64(2), int64(7)
  memory usage: 54.1 KB
  ```

- **Exploratory Data Analysis (EDA):**
  - Distribution plots for key features.
  - Correlation heatmaps to identify feature relationships.
  - Boxplots to detect outliers.
  

- **Model Training and Evaluation:**  
  - Logistic Regression, Decision Tree, and Random Forest classifiers were trained.  
  - Accuracy, precision, recall, and F1-score were computed.  
  - Confusion matrices and ROC curves were plotted.  
   

- **Warnings Encountered:**  
  ```
  ConvergenceWarning: lbfgs failed to converge. Increase the number of iterations or scale the data.
  ```
  *Potential Fix:* Normalize the data and adjust solver parameters.

## Contributing
- Fork the repository and create a feature branch.
- Make changes and submit a pull request.
- Report any issues or suggest improvements.


