# PRODIGY_ML_01
House Price Prediction using Linear Regression
This project implements a Linear Regression model to predict house prices based on:
->Living Area (Square Footage)
->Number of Bedrooms
->Number of Bathrooms
The model is built using Python and scikit-learn on the Kaggle House Prices dataset. 

Problem Statement
To predict the sale price of a house using basic housing features such as:
->GrLivArea (Above ground living area)
->BedroomAbvGr (Number of bedrooms)
->FullBath (Number of bathrooms)

Dataset
->Source: Kaggle – House Prices: Advanced Regression Techniques
->File Used: train.csv
->Target Variable: SalePrice

Technologies Used
->Python 3.x
->Pandas
->Matplotlib
->Seaborn
->Scikit-learn
->VS Code

Installation & Setup
1. Clone the Repository
git clone https://github.com/your-username/house-price-prediction.git
cd house-price-prediction
2. Install Required Libraries
python -m pip install pandas matplotlib seaborn scikit-learn
3.  Add Dataset
Download train.csv from Kaggle and place it in the project folder.
-> How to Run the Project
python house_price_prediction.py

Model Workflow
1. Load dataset using Pandas
2. Select relevant features
3. Handle missing values
4. Split data into training and testing sets
5. Train Linear Regression model
6. Evaluate model using MAE, MSE, and R² Score
7. Visualize Actual vs Predicted prices
Model Evaluation Metrics
->Mean Absolute Error (MAE)
->Mean Squared Error (MSE)
->R² Score
These metrics help evaluate the accuracy and performance of the regression model.

Visualization
A scatter plot is generated to compare:
->Actual House Prices
->Predicted House Prices
This helps visualize model performance.

Sample Prediction
The model can predict house prices for new input data:
new_house = [[2000, 3, 2]]  # Living Area, Bedrooms, Bathrooms



