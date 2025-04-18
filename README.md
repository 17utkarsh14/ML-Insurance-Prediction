# Insurance Prediction Model

This project implements a machine learning model to predict insurance charges based on various factors. It uses multiple regression techniques including Linear Regression, Ridge Regression, Lasso Regression, and ElasticNet Regression to predict insurance charges. The model is trained on the insurance dataset, and user input can be used to predict the insurance charges.

## Project Description

The project aims to predict the medical insurance charges of individuals based on various features like age, sex, BMI, number of children, smoking habits, and region. It uses machine learning models to fit the data and predict the charges.

### Models Used:
- **Linear Regression**
- **Ridge Regression**
- **Lasso Regression**
- **ElasticNet Regression**

### Key Features:
- Preprocessing the data (Encoding categorical variables, scaling numerical features)
- Model training and evaluation
- Feature importance from Lasso regression
- Model saving using Pickle

## Files in this Repository

1. `insurance.csv`: Dataset used for training the model.
2. `model.py`: Code for training and evaluating the models.
3. `linear_model.pkl`: Trained Linear Regression model (Pickle file).
4. `scaler.pkl`: StandardScaler object used to scale the input features.
5. `README.md`: This file, describing the project.

## How to Run

1. Clone this repository to your local machine.
2. Install required dependencies using the following command:
3. To train the model and make predictions, run the following command:

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

