# Expense Management System

The primary objective of this project is to predict a person's health insurance coverage based on various factors such as age, number of dependents, income, genetic risk, insurance plan, employment status, gender, marital status, BMI category, smoking habits, region, and medical history.

## Project Structure

- **artifacts/**: Contains models joblib files.
- **main**: Contains actual streamlit codes.
- **prediction_helper**: contains methods used to load models and predict the output and display it in frontend
- **requirements.txt**: Lists the required Python packages.
- **README.md**: Provides an overview and instructions for the project.


## Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/siddu28/ML-project-Health-Premium-Prediction.git
   ```
1. **Install dependencies:**:   
   ```commandline
    pip install -r requirements.txt
   ```

1. **Run the Streamlit app:**:   
   ```commandline
    streamlit run main.py
   ```