# IBM AI Engineering - Agent Guidance

This workspace contains a machine learning course covering supervised and unsupervised learning with Python.

## Project Overview

- **Purpose**: IBM AI Engineering course material with practical ML implementations
- **Structure**: Progressive notebooks from fundamentals to advanced techniques
- **Core Libraries**: scikit-learn, pandas, numpy, matplotlib, seaborn, plotly
- **Python Version**: 3.12.13+

## Course Content (C1_ML_with_Python/)

### Regression Methods
- **1_Simple-Linear-Regression**: Basic univariate regression
- **2_Mulitple-Linear-Regression**: Multivariate regression with feature selection
- **6_Regression_Trees_Taxi_Tip**: Tree-based regression on real taxi tip data

### Classification Methods  
- **3_Logistic_Regression**: Binary and multiclass logistic regression
- **4_Multi-class_Classification**: Multi-class classification techniques
- **8_KNN_Classification**: K-Nearest Neighbors classifier
- **7_decision_tree_svm_ccFraud**: Decision Trees and SVM for credit card fraud detection

### Tree-Based & Ensemble Methods
- **5_Decision_trees**: Decision tree fundamentals and pruning
- **9_Random_Forests_XGBoost**: Ensemble methods including Random Forests and gradient boosting

### Unsupervised Learning
- **10_K-Means-Customer-Seg**: K-Means clustering for customer segmentation

## Working with Notebooks

- All notebooks follow a consistent pattern: imports → data loading → EDA → model training → evaluation
- Datasets are loaded within notebooks (no separate data folder required)
- Use `jupyter notebook` or VS Code's built-in notebook support to execute cells
- Each notebook is self-contained and can be run independently
- Visualizations use matplotlib and plotly

## Common Tasks

**Running notebooks**: Open the `.ipynb` file and execute cells in order
**Adding new content**: Follow the existing notebook structure (markdown sections, imports, code cells)
**Modifying models**: Update model parameters in code cells and re-execute for retraining
**Data visualization**: Leverage matplotlib for static plots, plotly for interactive visualizations

## Development Notes

- Requirements are pinned in `requirements.txt` - update this when adding dependencies
- The main project template is in `main.py` but notebooks are the primary learning material
- `pyproject.toml` defines the project metadata
- No production deployment setup - this is educational material
