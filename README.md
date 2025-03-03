# Homework_MLFlow
Customer Churn Prediction with AI 🚀
Overview
Welcome to the Customer Churn Prediction Project! 🎯 This AI-powered application uses the Telco customer dataset to predict whether a customer is likely to churn. We’ve built a robust machine learning model using scikit-learn and deployed it as a web API using FastAPI. Whether you’re an aspiring data scientist, a business analyst, or someone interested in customer retention strategies, this project is for you! 🔍

💡 Why Customer Churn Prediction?
Customer churn is one of the most important metrics for any business. Predicting which customers are at risk of leaving can help companies take action early—improving customer retention strategies, increasing revenue, and fostering long-term growth. This project applies machine learning to solve a real-world business problem.

Tools & Technologies 🛠️
This project uses a collection of powerful tools to make the magic happen:

Git & GitHub: For seamless version control and collaboration 🖥️
Scikit-learn: A go-to library for machine learning in Python 📊
FastAPI: To create an ultra-fast web API to deploy our AI model ⚡
Joblib: To save and reload our trained model 💾
Uvicorn: The lightning-fast ASGI server for running FastAPI ⚡
Pandas: For all things data manipulation 🧑‍💻
MLflow: For track experiments, log models, and manage model versions. 📊
🚀 How to Get Started
Follow these simple steps to get the project up and running locally:

🖥️ 1. Clone the repository:
Start by cloning the repository to your local machine:

git clone https://github.com/limengkruy/fast-api-h02.git
cd fast-api-h02
⚡ 2. Install the required dependencies:
pip install -r requirements.txt
💾 3. Train the model:
Run the Python script to train the customer churn model and save it to a .pkl file:

cd modeling
python train.py
📊 4. MLflow Experiment Tracking
API Endpoints
Start MLflow UI:

mlflow ui
Access the MLflow UI at: http://127.0.0.1:5000

⚡ 5. Start the FastAPI server:
uvicorn main:app --reload
🧑‍💻 6. To make predictions, send a POST request to /predict with the customer data in JSON format.
API Endpoints
POST /predict: Predict customer churn based on the input data.

Example request:
