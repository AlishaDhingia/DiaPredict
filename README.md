
# DiaPredict – ML-Based Diabetes Prediction
Machine Learning model to predict diabetes using PIMA dataset.
## Project Overview
This project builds a machine learning model to predict the likelihood of diabetes based on clinical data using the PIMA Indian Diabetes dataset.

## Dataset
- Source: [PIMA Diabetes dataset](https://raw.githubusercontent.com/plotly/datasets/master/diabetes.csv)
- Contains features like Glucose, Blood Pressure, Insulin, BMI, Age, etc., and the target variable 'Outcome' (0 = no diabetes, 1 = diabetes).

## Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

## Steps
1. Load and explore dataset
2. Clean data by replacing invalid zeros with median values
3. Split data into training and testing sets
4. Train Random Forest Classifier
5. Evaluate model performance (accuracy, classification report)
6. Visualize feature correlation heatmap
7. Save trained model as `diabetes_model.pkl`

## Usage
- Run the `diabetes_prediction.ipynb` notebook step-by-step.
- Use the saved model to predict diabetes on new data.

## Sample Output
- Accuracy: Around 78-80%
- Classification report with precision, recall, and F1-score for both classes

## Author
Alisha Dhingia

---

Feel free to explore and improve the model!
