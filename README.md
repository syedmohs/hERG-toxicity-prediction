# hERG-toxicity-prediction
This script implements a machine learning pipeline for chemical compound analysis using molecular fingerprints. It includes functionality for calculating molecular fingerprints from SMILES strings, performing model training with various classifiers, and evaluating model performance with metrics like accuracy, precision, sensitivity, specificity, and AUC.
## Requirements

To run this code, you will need to install the following Python libraries:

### Python Packages:
- `pandas`: For data manipulation and analysis.
- `numpy`: For numerical operations.
- `scikit-learn`: For machine learning algorithms, preprocessing, model evaluation, and feature selection.
- `xgboost`: For XGBoost classifier and model training.
- `matplotlib`: For plotting graphs and visualizations.
- `seaborn`: For statistical data visualization.
- `tqdm`: For progress bars in loops.
- `torch`: For deep learning models using PyTorch.
- `shap`: For model interpretation and SHAP values.
- `rdkit`: For handling molecular structures and calculating fingerprints.
- `PyFingerprint`: For fingerprint generation from molecular structures.
- `glob`: For file pattern matching.
- `re`: For regular expressions.
- `statistics`: For basic statistical operations like mean calculation.
- `time`: For time-related operations.
- `warnings`: For handling warnings in the code.

### Installation Instructions:

You can install the required Python libraries using `pip`. Below are the installation commands:

```bash
pip install pandas numpy scikit-learn xgboost matplotlib seaborn tqdm torch shap rdkit PyFingerprint
