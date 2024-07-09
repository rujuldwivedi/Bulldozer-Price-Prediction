# Bulldozer Price Prediction (🚜)

Welcome to Bulldozer Price Prediction - a machine learning project dedicated to predicting the sale price of bulldozers. In this notebook, we'll navigate through a regression problem, aiming to forecast the sale prices of bulldozers using data from the [Kaggle Bluebook for Bulldozers competition](https://www.kaggle.com/c/bluebook-for-bulldozers/overview). The evaluation metric for this project is the Root Mean Square Log Error (RMSLE).

### Kaggle Bluebook for Bulldozers Competition
- [Competition Overview](https://www.kaggle.com/c/bluebook-for-bulldozers/overview)
- [Kaggle Dataset](https://www.kaggle.com/c/bluebook-for-bulldozers/data)

## Problem Definition

We approach this project as a regression problem, seeking to predict the sale prices of bulldozers. The inspiration and methodologies are drawn from the [fast.ai machine learning course](https://course18.fast.ai/ml).

## Machine Learning Modelling Framework

We'll follow a structured machine learning modelling framework with the goal of building a trained model capable of predicting bulldozer prices.
|:--:| 
| 6 Step Machine Learning Modelling Framework ([read more](https://whimsical.com/9g65jgoRYTxMXxDosndYTB)) |

### Tools Used in the Modelling Process

We'll utilize various tools for each step of the machine learning modelling process, including pandas, Matplotlib, NumPy for data analysis, and Scikit-Learn for machine learning and modelling tasks.
|:--:| 
| Tools which can be used for each step of the machine learning modelling process. |

## Workflow Overview

### 1. Data Collection and Loading

The dataset is loaded from the provided zipped file, allowing us to explore and understand the features related to bulldozer prices.

### 2. Data Exploration and Analysis

We perform an in-depth analysis of the dataset, visualizing key characteristics and gaining insights into the factors influencing bulldozer prices.

### 3. Data Preprocessing

Prior to model training, we preprocess the data, handling missing values, encoding categorical variables, and scaling numerical features for optimal model performance.

### 4. Model Selection and Training

We experiment with different regression models, evaluating their performance on the training data and selecting the most promising candidate.

### 5. Model Evaluation

The chosen model is evaluated using the RMSLE metric on a separate test dataset to assess its accuracy and generalization to new data.

### 6. Prediction

With a trained model in place, we can now predict the sale prices of bulldozers based on given characteristics.

## Getting Started

To run this project locally, follow these steps:

1. Clone the repository: `git clone https://github.com/rujuldwivedi/Bulldozer-Price-Prediction.git`
2. Install the required dependencies.
3. Run the Jupyter notebook: `jupyter notebook Bulldozer-Price-Regression.ipynb`

## Contributions

Contributions are welcome! Feel free to open issues, submit pull requests, or suggest improvements. Let's collaborate to enhance the accuracy and robustness of our bulldozer price prediction model.

## Acknowledgments

Special thanks to Kaggle for providing the dataset and the fast.ai community for valuable insights and methodologies.
