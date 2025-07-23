# ⚡ Electricity Bill Prediction Platform

Welcome to the **Electricity Bill Prediction Platform**! This project aims to predict electricity bills based on various factors such as consumption, demographic information, and environmental variables using machine learning models.

## Screenshots
![Screenshot 1](https://github.com/Raghavchawla13/AIML-Project/blob/main/ELectricitybill1.png)
![Screenshot 2](https://github.com/Raghavchawla13/AIML-Project/blob/main/Screenshot%202025-05-08%20230738.png)
![Screenshot 3](https://github.com/Raghavchawla13/AIML-Project/blob/main/Screenshot%202025-05-08%20230850.png)
![Screenshot 4](https://github.com/Raghavchawla13/AIML-Project/blob/main/Screenshot%202025-05-08%20231018.png)



## 🚀 Features

- **Upload Dataset**: Upload your dataset in CSV format and choose the target variable for prediction.
- **Model Selection**: Choose from multiple regression models (Linear Regression, Decision Tree Regressor, Random Forest Regressor) to train the model.
- **Performance Metrics**: View performance metrics such as MAE, MSE, RMSE, MAPE, R² Score, and Adjusted R² Score to evaluate model accuracy.
- **Visualization**: Interactive visualizations to compare actual vs predicted values and perform residual analysis.
- **Prediction Interface**: Input feature values to predict the electricity bill and see the result instantly.

## 🧑‍💻 Tech Stack

- **Python**: Core programming language.
- **Streamlit**: Framework for building the interactive web app.
- **Scikit-learn**: Used for building machine learning models and data preprocessing.
- **Plotly**: For visualizing the performance metrics and prediction results.

## ⚙️ Installation & Setup

To get this project running on your local machine, follow these steps:

###  Create and activate a virtual environment (optional but recommended)
```bash
python -m venv venv
# For Windows
venv\Scripts\activate
# For macOS/Linux
source venv/bin/activate
# Install dependencies
pip install -r requirements.txt
# Run the Streamlit app
streamlit run app.py
