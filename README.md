# Expense Management System

The primary objective of this project is to predict a person's health insurance coverage based on various factors such as age, number of dependents, income, genetic risk, insurance plan, employment status, gender, marital status, BMI category, smoking habits, region, and medical history.

## Project Structure

- **artifacts/**: Contains models joblib files.
- **main**: Contains actual streamlit codes.
- **prediction_helper**: contains methods used to load models and predict the output and display it in frontend
- **requirements.txt**: Lists the required Python packages.
- **README.md**: Provides an overview and instructions for the project.

## My Streamlit app
![Screenshot 2024-12-14 184636](https://github.com/user-attachments/assets/dfe924ea-7cea-4da7-8223-2a848cdfe997)

## A Demo Video
https://github.com/user-attachments/assets/8da84656-72f9-427a-a4b8-63f83ce18913

## Use my APP
https://lnkd.in/gmU25Qi2

## Skills gained
- **Machine learning**
- **Data cleaning**
- **EDA**
- **Data preprocessing**

## Project Explanation
Project Workflow

🚦 Steps Followed:

1. ➕ Data Cleaning

Handled missing values using statistical techniques such as mean, median, and mode to ensure data consistency.

2. 🔍 Exploratory Data Analysis (EDA)

Conducted univariate and bivariate analysis to study feature distributions and relationships and used box plots and the Interquartile Range (IQR) method to detect and handle outliers effectively.

3. 🔧 Feature Engineering

Applied Label Encoding to represent diseases as numeric values, emphasizing risk factors and used One-Hot Encoding (OHE) for categorical features to enhance model interpretability.
Plotted a heatmap to analyze feature correlations and calculated the Variance Inflation Factor (VIF) to remove multicollinear features.

4. ⚡ Error Analysis

Identified that the lower age group had a higher error percentage compared to the higher age group through error analysis (trained a model to measure error percentages).

Developed solutions to address this issue:

Collect more data for lower age groups.
Add new features to improve the model's ability to predict accurately.
Implemented the second approach by creating an extra feature, followed the same EDA process, and reduced the error percentage to 2%.

Built two separate models:

One for the lower age group.
One for the higher age group.

5. 🎨 Model Training and Segmentation

Trained two distinct models:

Higher Age Group Model: Retained the initial model since it had a low error percentage.

Lower Age Group Model: Incorporated the newly added feature, which initially caused inconsistencies across models.

Addressed this inconsistency by adding a dummy value for the extra feature in the higher age group model to ensure uniformity across both models.

💻 Deployment

Successfully deployed the project as a Streamlit web application for user interaction and ease of use.




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
