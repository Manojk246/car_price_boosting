🚗 Car Price Prediction
📌 Project Overview

This project predicts the selling price of used cars based on their features such as year, present price, kilometers driven, fuel type, seller type, transmission, and owner type.

The model is trained using machine learning algorithms (Random Forest, Gradient Boosting, etc.) and fine-tuned with GridSearchCV to achieve the best performance.
A Streamlit web app is built for interactive predictions

Car-Price-Prediction/
│-- app.py                # Streamlit app for prediction
│-- model_training.py      # Script for training & saving the model
│-- trained_model.sav      # Saved ML model (pickle file)
│-- requirements.txt       # Required dependencies
│-- CAR DETAILS FROM CAR DEKHO.csv  # Dataset
│-- README.md              # Project documentation

The dataset used is Car Details from CarDekho
.

Features include:

year → Year of manufacture

present_price → Current ex-showroom price (in lakhs)

kms_driven → Kilometers driven

fuel → Fuel type (Petrol, Diesel, CNG)

seller_type → Dealer or Individual

transmission → Manual or Automatic

owner → Number of previous owners

selling_price → Target variable (selling price in lakhs)

🤖 Model Training

The dataset is preprocessed (handling categorical variables, removing duplicates).

Multiple models were trained (Random Forest, Gradient Boosting, etc.).

Hyperparameter tuning was performed using GridSearchCV.

The best model is saved as trained_model.sav.
