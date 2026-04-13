# Income Forecasting Using Machine Learning - CS321 Project

## Overview
This project implements machine learning models to predict income levels (>$50K or ≤$50K) based on demographic and employment attributes from the UCI Adult Dataset. The goal is to develop and compare multiple classification algorithms to determine which model best predicts income levels using guided learning approaches.

## Dataset
- **Source**: UCI Adult Dataset (Census Income Database)
- **Records**: 48,842 instances
- **Features**: 15 attributes including age, workclass, education, occupation, marital status, race, gender, capital gains/losses, hours per week, and native country
- **Target Variable**: Income (binary classification: ≤$50K or >$50K)

## Project Contents

### Files
- **CS321_Shliakhov_Karayiannis.ipynb** - Main Jupyter notebook containing data analysis, preprocessing, model training, and evaluation
- **CS321_Report_Shliakov_Karayiannis.pdf** - Detailed project report with methodology, results, and findings
- **CS321_presentation_Shliakov_Karayiannis.pdf** - Presentation slides summarizing the project approach and conclusions

### Key Technologies & Libraries
- **Python 3**: Primary programming language
- **pandas**: Data manipulation and analysis
- **NumPy**: Numerical computations
- **scikit-learn**: Machine learning algorithms including:
  - Logistic Regression
  - Decision Tree Classifier
  - Random Forest Classifier
  - Neural Networks (MLPClassifier)
  - GridSearchCV for hyperparameter tuning
- **matplotlib**: Data visualization

## Methodology

### Data Preprocessing
- Feature extraction and encoding of categorical variables
- Handling missing values (marked as '?')
- Feature scaling using StandardScaler for neural networks

### Models Implemented
1. **Logistic Regression** - Baseline linear model
2. **Decision Tree Classifier** - Tree-based approach
3. **Random Forest Classifier** - Ensemble method
4. **Neural Networks (MLP)** - Deep learning approach

### Evaluation Metrics
- Model performance comparison
- Cross-validation and GridSearch for hyperparameter optimization
- Train-test split validation (stratified splitting for class imbalance)

## Usage

To run the notebook:
1. Ensure Python 3 and required libraries are installed
2. Open `CS321_Shliakhov_Karayiannis.ipynb` in Jupyter Notebook or Google Colab
3. Run cells sequentially to reproduce analysis and results

## Authors
- Yuri Shliakov
- Aggelos Karayiannis

## Notes
This project was completed as part of CS321 Machine Learning course requirements.
