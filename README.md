# Wine-Quality-Prediction
## Overview

This project aims to predict the quality of wines based on various features using machine learning models. The dataset used for this project contains information about different types of wines, including their chemical properties and quality ratings.

## Dataset

The dataset (`wineQT.csv`) used in this project includes the following columns:

- **Fixed Acidity**: The fixed acidity of the wine.
- **Volatile Acidity**: The volatile acidity of the wine.
- **Citric Acid**: The citric acid content in the wine.
- **Residual Sugar**: The residual sugar content in the wine.
- **Chlorides**: The chloride content in the wine.
- **Free Sulfur Dioxide**: The free sulfur dioxide content in the wine.
- **Total Sulfur Dioxide**: The total sulfur dioxide content in the wine.
- **Density**: The density of the wine.
- **pH**: The pH level of the wine.
- **Sulphates**: The sulphates content in the wine.
- **Alcohol**: The alcohol content in the wine.
- **Wine Type**: Categorical column indicating the type of wine (Red or White).
- **Quality**: The quality rating of the wine (target variable).

## Setup
1. Clone the repository:

   ```bash
   git clone https://github.com/Abhiruchi37/Wine-Quality-Prediction.git
   cd Wine-Quality-Prediction
   ```

2. Install the required libraries:

   ```bash
   pip install -r requirements.txt
   ```

3. Load your wine quality dataset into the appropriate file.

4. Run the recommendation system:

   ```bash
   jupyter notebook Wine_Quality_Prediction.ipynb

   ```

## Model Performance

The machine learning models (SVM, GradientBoosting) were trained and evaluated using various metrics. The final model achieved an accuracy of 70% on the test set.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

