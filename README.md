# Client Churn Prediction for Interconnect

## Overview
This project aims to forecast client churn for the telecom operator Interconnect. By predicting which customers are likely to leave, the company can proactively offer promotional codes and special plan options to retain them. The project leverages customer data, including personal details, plan information, and contract specifics, to build predictive models that identify potential churners.

## Description
Interconnect provides a variety of telecommunication services to its customers. The main services include landline communication and internet connectivity. The company also offers additional services like internet security, technical support, cloud storage, and TV streaming. Customers have flexibility in their payment methods and contract durations, which can be monthly or span 1 to 2 years.

**Interconnect's Services**

Interconnect offers the following services:

1. **Landline Communication**: Customers can connect multiple telephone lines simultaneously.
2. **Internet**: The network is provided either through a telephone line (DSL) or via a fiber optic cable.

Additional services include:

- **DeviceProtection**: Antivirus software for internet security.
- **OnlineSecurity**: A blocker for malicious websites.
- **TechSupport**: A dedicated technical support line.
- **OnlineBackup**: Cloud storage and data backup.
- **StreamingTV**: TV streaming service.
- **StreamingMovies**: Access to a movie directory.

Clients can select from various contract types, such as monthly payments or 1- to 2-year contracts. They also have the option to pay through multiple methods and receive electronic invoices after each transaction.

**Data Description**

The project utilizes data from various sources, compiled into the following files:

- `contract.csv`: Contains contract information for each client.
- `personal.csv`: Includes personal data of the clients.
- `internet.csv`: Provides details about internet services subscribed by clients.
- `phone.csv`: Contains information about the telephone services used by clients.

Each file has a `customerID` column that uniquely identifies each client. The data is up-to-date as of February 1, 2020.

## Objectives
The primary goal of this project is to accurately predict which clients are likely to churn. By achieving this, Interconnect can:

- Reduce client churn rates by offering targeted promotions.
- Enhance customer satisfaction through personalized offers.
- Improve revenue retention by preventing customer loss.

## Libraries
The following libraries and tools were used in the project:

- **pandas**: For data manipulation and analysis.
- **numpy**: For numerical computations.
- **matplotlib**: For creating visualizations.
- **seaborn**: For statistical data visualization.
- **datetime**: For handling date and time-related data.
- **lightgbm**: For implementing gradient boosting models.
- **xgboost**: For building advanced gradient boosting models.
- **sklearn**: For machine learning algorithms and model evaluation.

## Conclusion
This project provides a comprehensive solution for predicting client churn at Interconnect. By leveraging customer data and machine learning models, the company can proactively identify clients at risk of leaving and take necessary actions to retain them. Future improvements could involve enhancing the model's accuracy, integrating additional data sources, and developing real-time prediction capabilities.
