# Financial Inclusion Prediction

## Introduction

This project involves working on a dataset that contains demographic information and details about the use of financial services by approximately 33,600 individuals across East Africa. The objective is to develop a machine learning model to predict which individuals are most likely to have or use a bank account, aiding in the efforts towards financial inclusion.

## Problem Statement

The main goal of this project is to predict the likelihood of individuals having or using a bank account based on various demographic and socio-economic indicators. Financial inclusion is crucial as it ensures that individuals and businesses have access to useful and affordable financial products and services that meet their needs—transactions, payments, savings, credit, and insurance—delivered in a responsible and sustainable way.

## Dataset Description

The dataset includes demographic information and the financial services used by individuals in East Africa. The columns in the dataset are as follows:

- **country**: String, the country where the respondent is located.
- **year**: Integer, the year of the survey.
- **uniqueid**: String, a unique identifier for each respondent.
- **bank_account**: Binary, indicates whether the respondent has a bank account (1 = yes, 0 = no).
- **location_type**: String, type of location (e.g., urban, rural).
- **cellphone_access**: Binary, indicates whether the respondent has access to a cellphone.
- **household_size**: Integer, number of people in the respondent's household.
- **age_of_respondent**: Integer, age of the respondent.
- **gender_of_respondent**: String, gender of the respondent.
- **relationship_with_head**: String, relationship of the respondent with the head of the household.
- **marital_status**: String, marital status of the respondent.
- **education_level**: String, highest level of education attained by the respondent.
- **job_type**: String, type of job or occupation of the respondent.

## Objectives

1. **Predict Bank Account Ownership**: Develop a machine learning model to accurately predict the likelihood of an individual having or using a bank account.
2. **Identify Key Factors**: Analyze the dataset to identify key factors that contribute to financial inclusion.
3. **Provide Recommendations**: Suggest actionable insights and strategies to improve financial inclusion based on model predictions and analysis.

## Tools and Libraries

This project utilizes the following tools and libraries:
- **Python**: Programming language for data analysis and modeling.
- **Pandas**: For data manipulation and analysis.
- **Scikit-learn**: For machine learning modeling.
- **Matplotlib/Seaborn**: For data visualization.
- **Streamlit**: For deploying the machine learning model as a web application.

## Installation

To get started with the project, you need to have Python installed. Install the necessary libraries using pip:

```sh
pip install pandas scikit-learn matplotlib seaborn streamlit
```

## Usage

1. **Clone the repository:**

```sh
git clone https://github.com/Oluwaseun25/Financial_Inclusion.git
cd Financial_Inclusion
```

2. **Run the analysis script:**

The main analysis and modeling are contained in the `Financial_Inclusion.py` script. Run this script to perform the data analysis and train the machine learning model:

```sh
python analysis.py
```

3. **Deploy the Streamlit app:**

The Streamlit app is contained in the `app.py` script. Run this script to deploy the web application:

```sh
streamlit run app.py
```

## Analysis and Model Development

### Data Preprocessing

- **Cleaning**: Handle missing values and correct any inconsistencies in the dataset.
- **Encoding**: Convert categorical variables into numerical values.
- **Scaling**: Standardize the numerical features to improve model performance.

### Model Training

- **Feature Selection**: Identify and select the most relevant features for the model.
- **Model Selection**: Evaluate different machine learning algorithms (e.g., logistic regression, decision trees, random forest) to select the best-performing model.
- **Model Training**: Train the selected model on the training data and evaluate its performance on the validation set.

### Results and Insights

- **Feature Importance**: Analyze which features have the most significant impact on predicting bank account ownership.
- **Predictive Accuracy**: Assess the accuracy and reliability of the model in predicting financial inclusion.

## Recommendations

- **Targeted Financial Programs**: Develop targeted financial programs and interventions for groups identified as less likely to have bank accounts based on the model's predictions.
- **Increase Access to Technology**: Implement measures to increase access to technology, such as cellphones, which can facilitate financial inclusion.
- **Educational Campaigns**: Conduct educational campaigns to raise awareness about the benefits of having a bank account and other financial services.

## Conclusion

By developing a robust machine learning model and analyzing key demographic and socio-economic factors, this project aims to provide valuable insights into financial inclusion in East Africa, enabling better-targeted interventions and strategies to promote financial inclusion.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

We thank the Zindi platform for hosting the challenge and providing the dataset. We also appreciate the open-source community for the tools and libraries used in this project.
