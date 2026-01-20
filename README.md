# Laptop Price Prediction

A machine learning project that predicts laptop prices based on various hardware and software specifications.

## Overview

This project uses supervised machine learning techniques to predict laptop prices (in Euros) based on features such as:

- **Brand/Company** - Manufacturer of the laptop
- **Product Type** - Ultrabook, Notebook, Gaming, etc.
- **Screen Size** - Display size in inches
- **Screen Resolution** - Including IPS Panel, Retina Display, etc.
- **CPU** - Processor specifications
- **RAM** - Memory capacity
- **Storage** - SSD, HDD, or hybrid storage
- **GPU** - Graphics card specifications
- **Operating System** - macOS, Windows, Linux, etc.
- **Weight** - Laptop weight

## Dataset

The dataset (`laptop_data.csv`) contains **1,303 laptop entries** with 13 features including the target variable (Price in Euros).

## Project Structure

```
├── LPP.ipynb          # Main Jupyter notebook with analysis and models
├── laptop_data.csv    # Dataset containing laptop specifications and prices
└── README.md          # Project documentation
```

## Methodology

The notebook (`LPP.ipynb`) covers:

1. **Data Loading & Exploration** - Understanding the dataset structure
2. **Exploratory Data Analysis (EDA)** - Visualizing relationships between features
3. **Data Preprocessing** - Handling categorical variables and feature engineering
4. **Model Training** - Training various regression models including:
   - Linear Regression
   - Decision Tree Regressor
   - Random Forest Regressor
5. **Hyperparameter Tuning** - Using GridSearchCV for optimization
6. **Model Evaluation** - Comparing models using R² Score, MAE, and Max Error

## Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Usage

1. Clone the repository
2. Install the required packages:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
3. Open and run the Jupyter notebook:
   ```bash
   jupyter notebook LPP.ipynb
   ```

## Results

The Random Forest Regressor achieves the best performance with:
- **Training R² Score**: ~98.3%
- **Test R² Score**: ~89.6%

## License

This project is for educational purposes.
