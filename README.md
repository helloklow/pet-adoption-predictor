# Pet Adoption Predictor

## Introduction
Pet Adoption Predictor is a data science project utilizing Austin Animal Center 
data on animal shelter outcomes. This project aims to predict the likelihood of 
a shelter animal being adopted based on characteristics such as age, breed, sex, 
and whether the animal has been spayed or neutered. A command line intake tool 
allows shelter staff to input an animal's details and receive an instant adoption 
likelihood prediction. Please note, this project is educational only and is not 
guaranteed to provide accurate predictions.

## Project Scope
This project is intended to showcase fundamental data science and machine learning 
principles. The primary objectives were to demonstrate thorough exploratory data 
analysis including visualizations, feature engineering, model selection, and 
hyperparameter tuning. The project features a basic, interactive command line program, which accepts input on an animal's characteristics and returns their adoption likelihood.

## Data Source
[Austin Animal Center Outcomes via Socrata API](https://data.austintexas.gov/resource/9t4d-g238.json)\
Live shelter outcome data from the Austin Animal Center, containing 170,000+ records.

## Tech Stack
**Language:** Python
**Data Ingestion:** Requests
**Data Analysis:** Matplotlib, Numpy, Pandas, Seaborn
**Modeling:** Scikit-learn, Joblib

## Installation & Usage

### Setup
1. Clone the repository
   git clone https://github.com/helloklow/pet-adoption-predictor.git
   cd pet-adoption-predictor

2. Create and activate a virtual environment
   python3 -m venv venv
   source venv/bin/activate

3. Install dependencies
   pip install -r requirements.txt

4. Fetch the data by running all cells in notebooks/01_data_ingestion.ipynb

5. Run all cells in notebooks/03_cleaning_feature_engineering.ipynb to generate
   the cleaned dataset

6. Run all cells in notebooks/04_modeling.ipynb to train and save the model

### Running the Prediction Tool
Open notebooks/05_prediction.ipynb and run all cells. The intake tool will
prompt you for animal details and return an adoption likelihood prediction.

## Contributors
This app was built by [Kelsey Low](https://github.com/helloklow) as a personal portfolio project.
