
# Credit Card Approval Prediction

Welcome to the Credit Card Approval Prediction project! This repository contains code and resources for building a machine learning model to predict credit card approval based on customer information.
![Firefly CREDIT CARD Approval Prediction by AI 89047](https://github.com/user-attachments/assets/f4222893-901b-4025-8205-9812325d4422)

## Overview

The goal of this project is to develop a predictive model to determine whether a credit card application should be approved or rejected. We utilize various features from customer data and credit scoring information to train our machine learning model.

## Datasets

### 1. Application Data (`Credit_Card.csv`)

This dataset contains the following features for each credit card application:

- `Ind_ID`: Client ID
- `Gender`: Gender information
- `Car_owner`: Indicator of car ownership
- `Propert_owner`: Indicator of property ownership
- `Children`: Count of children
- `Annual_income`: Annual income
- `Type_Income`: Income type
- `Education`: Education level
- `Marital_status`: Marital status
- `Housing_type`: Living style
- `Birthday_count`: Backward count from current day (0). -1 means yesterday.
- `Employed_days`: Backward count from current day (0). Positive value means the individual is currently unemployed.
- `Mobile_phone`: Indicator of mobile phone ownership
- `Work_phone`: Indicator of work phone ownership
- `Phone`: Indicator of any phone number
- `EMAIL_ID`: Indicator of email ID
- `Type_Occupation`: Occupation type
- `Family_Members`: Family size

### 2. Credit Status Data (`Credit_card_label.csv`)

This dataset contains the target variable for the credit card approval prediction:

- `ID`: Joining key between application data and credit status data (same as `Ind_ID`)
- `Label`: 
  - `0`: Application approved
  - `1`: Application rejected

## Project Structure

- `data/`: Contains the datasets used for training and testing the model.
- `notebooks/`: Jupyter notebooks for exploratory data analysis (EDA), feature engineering, and model development.
- `src/`: Source code for data processing, model training, and evaluation.
- `requirements.txt`: Python dependencies required for this project.
- `README.md`: This file.


## Usage

1. **Data Exploration**: Begin by exploring the data using the Jupyter notebooks in the `notebooks/` directory.
2. **Feature Engineering**: Perform feature engineering and preprocessing on the data.
3. **Model Training**: Train different machine learning models using the source code in the `src/` directory.
4. **Evaluation**: Evaluate model performance and make predictions.

:



## Contributing

Feel free to submit issues or pull requests. If you would like to contribute, please ensure that your code adheres to the existing style and passes all tests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any questions or feedback, please reach out to [your-email@example.com](nirmalsarkarcv@example.com).
