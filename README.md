# Linear Regression Project

## Introduction
This repository hosts a Linear Regression analysis for an Ecommerce company based in New York City. The company operates both online and offline, offering personal stylist sessions in-store and facilitating purchases via a mobile app or website. The analysis's goal is to determine whether the company should focus on enhancing their mobile app or their website experience.

## Dataset
The `Ecommerce.csv` file used in this analysis contains various metrics about the customers' interaction with the company's services. This dataset was obtained from Jose Portilla at Pieran Training.

## Analysis
The analysis involves building a Linear Regression model to identify the relationship between how much time customers spend on different platforms (app and website) and the amount of money they spend. The notebook `02-Linear Regression Project.ipynb` details the model building and interpretation process.

## Final Findings
The Linear Regression model provided the following coefficients, suggesting which factors have more impact on the yearly spend:

| Feature                | Coefficient |
|------------------------|-------------|
| Avg. Session Length    | 25.981550   |
| Time on App            | 38.590159   |
| Time on Website        | 0.190405    |
| Length of Membership   | 61.279097   |

## Recommendations
Based on the model's findings, the recommendations are:

1. To focus more on the mobile app, given its significant impact on revenue.
2. To improve the website's functionality to leverage the untapped market potential and increase overall revenue.

## Repository Contents
- `02-Linear Regression Project.ipynb`: A Jupyter notebook containing the detailed linear regression analysis and findings.
- `Ecommerce Customers`: A folder which is expected to include data files and potentially scripts related to the customer analysis.
- `README.md`: The markdown document providing an overview of this repository and the analysis.

For more details on the analysis and findings, refer to the Jupyter notebook included in this repository.

