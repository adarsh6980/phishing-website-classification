# Phishing Website Classification

This project implements machine learning models to detect phishing websites using Decision Tree and k-Nearest Neighbors algorithms.

## Project Structure

```
phishing-classification/
│
├── data/
│   └── phishing_data.csv  # Dataset for training and testing
│
├── 01_Decision_Tree.ipynb  # Decision Tree implementation
├── 02_kNN.ipynb           # k-Nearest Neighbors implementation
│
├── plots/                 # Saved visualization plots
│   ├── dt_confusion_matrix.png
│   ├── dt_feature_importance.png
│   ├── knn_confusion_matrix.png
│   └── knn_k_values_accuracy.png
│
└── models/                # Saved models
    ├── decision_tree_model.pkl
    └── knn_model.pkl
```

## Setup

1. Clone the repository
2. Install the required packages:
   ```
   pip install -r requirements.txt
   ```
3. Place your dataset in the `data/` directory
4. Open and run the Jupyter notebooks in order:
   - `01_Decision_Tree.ipynb`
   - `02_kNN.ipynb`

## Dependencies

- Python 3.7+
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- jupyter

## Usage

1. Load and preprocess your dataset
2. Run the model training cells in the notebooks
3. View the generated plots in the `plots/` directory
4. The trained models will be saved in the `models/` directory
