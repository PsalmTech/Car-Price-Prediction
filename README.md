# 🚗 Car Price Prediction with Machine Learning

## 📌 Overview

Car price prediction is an important problem in the automotive industry. The price of a car depends on several factors like brand, features, mileage, fuel type, and more. This project aims to build a machine learning model that predicts the selling price of a car based on its specifications.

## 📂 Dataset

The dataset contains information about used cars, including their age, fuel type, transmission, and other key features affecting their price.

### Columns in the Dataset:

Car_Name – Name of the car

Year – Year of purchase

Selling_Price – Selling price of the car (target variable)

Present_Price – Showroom price when the car was new

Driven_kms – Distance traveled by the car in kilometers

Fuel_Type – Type of fuel used (Petrol/Diesel/CNG)

Selling_type – Individual or Dealer sale

Transmission – Manual or Automatic

Owner – Number of previous owners


## 🛠️ Technologies Used

Python

Pandas & NumPy (for data manipulation)

Matplotlib & Seaborn (for visualization)

Scikit-Learn (for machine learning models)

Google Colab (for execution)


## 📜 Project Structure

📁 Car-Price-Prediction
│── 📄 Car_Price_Predict.ipynb  # Jupyter Notebook with analysis
│── 📄 Car_Data.csv  # Dataset
│── 📄 README.md  # Project documentation
│── 📄 requirements.txt  # Required libraries

## 🚀 How to Run

1. Clone this repository:

git clone https://github.com/PsalmTech/Car-Price-Prediction.git
cd Car-Price-Prediction


2. Install dependencies:

pip install -r requirements.txt


3. Run the Jupyter Notebook:

Open Google Colab

Upload the Car_Price_Predict.ipynb notebook

Execute the code cells in order


### 📊 Machine Learning Models

✔️ Linear Regression
✔️ Random Forest Regressor

### 📈 Model Evaluation Metrics

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

Root Mean Squared Error (RMSE)

R² Score


## 🏆 Results & Findings

The Random Forest model performed better than Linear Regression in predicting car prices.

Important factors: Car age, present price, fuel type, and transmission type significantly influence the selling price.


## 🤝 Contributing

Contributions are welcome! Fork this repository, make improvements, and submit a pull request.

## 📜 License

This project is licensed under the MIT License.
