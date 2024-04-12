# Almaty-Apartment-Price-Predictor
#Overview
This project focuses on scraping, analyzing, and predicting apartment prices in the Medeu district of Almaty using data from the Krisha.kz website. The primary goal is to gain practical experience with the XGBoost library and other machine learning techniques in Python.

#Features
Data Collection: Scrapes apartment listing data including price, number of rooms, area, and floor.
Data Transformation: Converts raw data into a structured format suitable for analysis.
Model Training: Uses XGBoost and Linear Regression models to predict apartment prices.
Model Evaluation: Employs cross-validation and grid search to fine-tune and evaluate model performance.
#Prerequisites
Before running this project, ensure you have the following packages installed:

BeautifulSoup4: pip install beautifulsoup4
Requests: pip install requests
Pandas: pip install pandas
Matplotlib: pip install matplotlib
Seaborn: pip install seaborn
NumPy: pip install numpy
Scikit-learn: pip install scikit-learn
XGBoost: pip install xgboost
Usage
Data Scraping: The script first determines the number of pages to scrape, then loops through each page to collect data on apartment prices and details.
Data Processing: Cleans and structures the data into a DataFrame for analysis. Additional features such as whether an apartment is on the first or last floor are engineered from the data.
Data Preprocessing: Implements pipelines for numerical and categorical data preprocessing.
Model Training: Trains an XGBoost regressor model with parameters optimized through grid search.
Model Evaluation: Evaluates the model using R² scores from cross-validation.
