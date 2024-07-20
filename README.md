Certainly! Here's the plain text version of the README content:

---

# Boston Housing Price Prediction

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction
This project aims to predict housing prices in Boston using machine learning models. We utilize Decision Trees and Random Forests for regression and evaluate their performance. The repository includes detailed steps for data preprocessing, model training, prediction, and evaluation.

## Dataset
The dataset used in this project is the Boston Housing dataset, which contains various features such as:
- ZN: Proportion of residential land zoned for lots over 25,000 sq. ft.
- PTRATIO: Pupil-teacher ratio by town
- MEDV: Median value of owner-occupied homes in $1000s

## Project Structure
```
├── data
│   └── boston.csv           # Dataset
├── images
│   └── plots                # Directory to save plots
├── notebooks
│   └── analysis.ipynb       # Jupyter notebook for analysis
├── src
│   └── main.py              # Main script for running the project
├── README.md
├── requirements.txt         # Required packages
└── LICENSE
```

## Usage
1. Ensure you have the dataset in the `data` directory.
2. Run the main script:
   ```
   python src/main.py
   ```

## Results
### Scatter Plot of Actual vs. Predicted Values
- **Random Forest**:
  ![Random Forest](images/plots/random_forest_scatter.png)
- **Decision Tree**:
  ![Decision Tree](images/plots/decision_tree_scatter.png)

### Residuals Distribution
- **Random Forest**:
  ![Random Forest Residuals](images/plots/random_forest_residuals.png)
- **Decision Tree**:
  ![Decision Tree Residuals](images/plots/decision_tree_residuals.png)

### Model Evaluation Metrics
- **Mean Absolute Error (MAE)**:
  - Random Forest: `mae_forest`
  - Decision Tree: `mae_tree`
- **Mean Squared Error (MSE)**:
  - Random Forest: `mse_forest`
  - Decision Tree: `mse_tree`
- **R² Score**:
  - Random Forest: `r2_forest`
  - Decision Tree: `r2_tree`

## Contributing
Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Create a new Pull Request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---
