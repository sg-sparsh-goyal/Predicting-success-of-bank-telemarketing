# Predict the Success of Bank Telemarketing

This project aims to predict whether a client will subscribe to a bank term deposit based on data collected from direct marketing campaigns. The goal is to develop a machine learning model that can accurately predict the likelihood of subscription. This prediction can help the bank optimize its marketing strategy and improve targeting efforts for future campaigns.

## 📊 About the Data

The dataset is sourced from [Kaggle](https://www.kaggle.com/competitions/predict-the-success-of-bank-telemarketing/data). It is related to direct marketing campaigns of a banking institution, conducted through phone calls. Often, multiple contacts with the same client were required to determine if the product (bank term deposit) would be subscribed to (`yes`) or not (`no`).

### Files
- **`train.csv`**: The training dataset.
- **`test.csv`**: The test dataset.
- **`sample_submission.csv`**: A sample submission file in the correct format.

### Data Dictionary
| **Feature**       | **Description**                                                                                  |
|--------------------|--------------------------------------------------------------------------------------------------|
| `last_contact_date` | Last contact date.                                                                              |
| `age`              | Age of the client (numeric).                                                                     |
| `job`              | Type of job.                                                                                     |
| `marital`          | Marital status (categorical: "married", "divorced", "single"; note: "divorced" includes widowed). |
| `education`        | Education level (categorical: "unknown", "secondary", "primary", "tertiary").                    |
| `default`          | Has credit in default? (binary: "yes", "no").                                                    |
| `balance`          | Average yearly balance, in euros (numeric).                                                     |
| `housing`          | Has housing loan? (binary: "yes", "no").                                                        |
| `loan`             | Has personal loan? (binary: "yes", "no").                                                       |
| `contact`          | Contact communication type (categorical: "unknown", "telephone", "cellular").                   |
| `duration`         | Last contact duration, in seconds (numeric).                                                    |
| `campaign`         | Number of contacts performed during this campaign and for this client (numeric).                |
| `pdays`            | Number of days since the client was last contacted from a previous campaign (numeric, -1 if not previously contacted). |
| `previous`         | Number of contacts performed before this campaign and for this client (numeric).                |
| `poutcome`         | Outcome of the previous marketing campaign (categorical: "unknown", "other", "failure", "success"). |
| `target`           | Has the client subscribed a term deposit? (binary: "yes", "no").                                 |

---

## 🤖 Machine Learning Workflow

1. **Data Loading**: Load and inspect the datasets.
2. **EDA**: Visualize data patterns and relationships.
3. **Data Preprocessing**: Clean and preprocess data for training.
4. **Model Training**: Train machine learning models to predict the target variable.
5. **Model Analysis**: Evaluate model performance using metrics such as accuracy.
6. **Hyperparameter Tuning**: Optimize model parameters for better performance.
7. **Prediction**: Generate predictions on test data and prepare submission files.

---


## Evaluation and Model Comparison

![Screenshot 2025-01-12 143001](https://github.com/user-attachments/assets/a6ec9d1e-7ca6-4021-a563-d0f40878cec2)


![Screenshot 2025-01-12 143015](https://github.com/user-attachments/assets/fb2fcf4e-3f44-4f4a-87b1-922599b00433)


![Screenshot 2025-01-12 143031](https://github.com/user-attachments/assets/b161343c-02a5-45cd-9ea5-d1c395418a43)

