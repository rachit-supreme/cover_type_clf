# Forest Cover Type Classification

## Overview
This machine learning project aims to predict forest cover types based on cartographic variables. The model classifies different types of forest cover using various environmental and geological features.

## Dataset
The dataset contains observations of forest cover types from the Roosevelt National Forest in northern Colorado. Each observation includes:
- Elevation
- Aspect
- Slope
- Distance features
- Soil type
- Wilderness area designation
- Forest cover type (target variable)

## Project Structure
```
cover_type_clf/
│
├── dataset/               # Dataset files
├── model/                 # pkl files of trained model
├── predictions/           # output of model prediction
└── README.md
└── requirements.txt
```

## Features
- Data preprocessing and exploration
- Feature engineering and selection
- Multiple classification algorithms comparison
- Model evaluation and validation
- Performance metrics analysis

## Requirements
- Python 3.8+
- scikit-learn
- pandas
- numpy
- matplotlib
- seaborn

## Installation
```bash
git clone https://github.com/rachit-supreme/cover_type_clf.git
cd cover_type_clf
pip install -r requirements.txt
```

## Usage
1. Run the data preprocessing notebook
2. Execute model training scripts
3. Evaluate results using the analysis notebook

## Results

### Model Performance
The Random Forest Classifier achieved the following metrics:

#### Accuracy
- Overall Accuracy: 0.95 (95%)

#### Classification Report
```
              precision    recall  f1-score   support

           1       0.97      0.96      0.96      1506
           2       0.91      0.93      0.92      1476
           3       0.89      0.92      0.90       610
           4       0.95      0.93      0.94       369
           5       0.96      0.93      0.95       378
           6       0.97      0.96      0.97       383
           7       0.98      0.97      0.98       364

    accuracy                           0.95      5086
   macro avg       0.95      0.94      0.94      5086
weighted avg       0.95      0.95      0.95      5086
```

### Key Findings
- Excellent performance across all 7 forest cover types
- Highest precision for Class 7 (98%)
- Most balanced F1-scores ranging from 90% to 98%
- Robust performance even with imbalanced class distribution

## Contributors
- Rachit
