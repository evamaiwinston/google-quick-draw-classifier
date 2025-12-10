# Image Classification Project

## Contents of the Repository
This repository contains all the code, data, and documentation needed to reproduce the image classification analysis. It includes Jupyter notebooks for exploratory data analysis and model development, parquet files with training and testing data, and a final report summarizing the results.

### Software and Platform
- **Python:** Version 3.12+
- **Jupyer Notebooks:* For running `.ipynb` files
- **Required Packges:**
  - Test
- **Operating System:** Windows/Mac

### Map of Documentation

```
image-classifier/
│
├── data/
│ └── training_data.parquet # 80% of data for model training
│ └── testing_data.parquet # 20% of data for model evaluation
│
├── notebooks/
│ └── EDA.ipynb # Descriptive Analysis Notebook
│ └── final_evaluation.ipynb # Final Model Training and Evaluation
│ └── gradient_boosting.iypnb # Gradient Boosting Model Development
│ └── neural_network.iypnb # Neural Network Model Development
│ └── random_forest.ipynb # Random Forest Model Development
│
├── output/
│ └── TBD
│ └── TBD
│ └── TBD
│
├── final_report.pdf # Final Report for the Project
├── .gitignore # Git ignore file
├── README.md # This file
└── requirements.txt # Python package dependencies
```

# Image Classification Project

This project develops and evaluates machine learning models for image classification. The repository includes exploratory data analysis, model training notebooks, and performance evaluation using training and testing datasets.

## Contents of the Repository

This repository contains all the code, data, and documentation needed to reproduce the image classification analysis. It includes Jupyter notebooks for exploratory data analysis and model development, parquet files with training and testing data, and a final report summarizing the results.

## Software and Platform

### Required Software
- **Python**: Version 3.8 or higher
- **Jupyter Notebooks**: For running `.ipynb` files

### Required Packages
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- PyTorch

### Operating System
- Compatible with Mac, Windows, and Linux

## Map of Documentation

```
image-classifier/
│
├── data/
│   ├── training_data.parquet    # 80% of data for model training
│   └── testing_data.parquet     # 20% of data for model evaluation
│
├── notebooks/
│   ├── EDA.ipynb                # Exploratory data analysis
│   ├── final_evaluation.ipynb   # Final model evaluation and comparison
│   ├── gradient_boosting.ipynb  # Gradient boosting model development
│   ├── neural_network.ipynb     # Neural network model development
│   └── random_forest.ipynb      # Random forest model development
│
├── output/
│   └── (Model outputs and results will be stored here)
│
├── final_report.pdf             # Comprehensive project report
├── .gitignore                   # Git ignore file
├── README.md                    # This file
└── requirements.txt             # Python package dependencies
```

## Getting Started

1. Install the required Python packages:
   ```bash
   pip install -r requirements.txt
   ```

2. Open and run the notebooks in the following order:
   - Start with `EDA.ipynb` for data exploration
   - Run model development notebooks (`random_forest.ipynb`, `gradient_boosting.ipynb`, `neural_network.ipynb`)
   - Review results in `final_evaluation.ipynb`

3. Refer to `final_report.pdf` for detailed analysis and conclusions.
