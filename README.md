# ONLINE_SHOPPERS_PURCHASING_INTENSION
Predicting online shopper purchase intent using machine learning models and feature engineering on website interaction data.

### Overview
This project aims to develop a predictive model to forecast whether an online shopper will generate revenue based on their browsing behavior on an e-commerce website. The model utilizes a dataset containing various features related to user interactions, including page views, time spent on pages, and other behavioral metrics.

### Dataset
The dataset used for this project is called `online_shoppers_intention.csv`, containing the following columns:

- **Administrative**: Number of administrative pages viewed
- **Administrative_Duration**: Total time spent on administrative pages
- **Informational**: Number of informational pages viewed
- **Informational_Duration**: Total time spent on informational pages
- **ProductRelated**: Number of product-related pages viewed
- **ProductRelated_Duration**: Total time spent on product-related pages
- **BounceRates**: Percentage of single-page visits
- **ExitRates**: Percentage of exits from the site
- **PageValues**: Average value of a page based on the revenue generated
- **SpecialDay**: Indicates if the visit occurred on a special day (e.g., holiday)
- **Month**: Month of the visit
- **OperatingSystems**: The operating system used by the visitor
- **Browser**: The browser used by the visitor
- **Region**: The region where the visitor is located
- **TrafficType**: Type of traffic (e.g., direct, referral)
- **VisitorType**: Whether the visitor is a new or returning visitor
- **Weekend**: Indicates if the visit occurred on a weekend
- **Revenue**: Target variable indicating whether the visitor made a purchase

### Project Structure

```
/online_shoppers_intention_prediction
│
├── data/
│   └── online_shoppers_intention.csv      # Dataset used for training and testing
│
├── models/
│   └── best_model.joblib                 # Saved model after hyperparameter tuning
│
├── notebooks/
│   └── exploratory_data_analysis.ipynb   # Jupyter notebook for exploratory data analysis (EDA)
│   └── model_training.ipynb              # Jupyter notebook for model training and evaluation
│
├── src/
│   ├── data_preprocessing.py             # Script for data cleaning and preprocessing
│   ├── feature_selection.py              # Script for feature selection process
│   └── model_evaluation.py               # Script for evaluating model performance
│
└── README.md                            # Project documentation
```

### Installation and Setup

1. **Clone the repository**:
    ```bash
    git clone <repository-url>
    cd online_shoppers_intention_prediction
    ```

2. **Install required packages**:
    ```bash
    pip install -r requirements.txt
    ```

### Usage

#### Data Preprocessing:
Run `data_preprocessing.py` to clean and preprocess the dataset.

#### Feature Selection:
Execute `feature_selection.py` to select relevant features for modeling.
