# Homework_MLFlow

## Tools & Technologies

This project uses a collection of powerful tools to make the magic happen:

- **Git & GitHub**: For seamless version control and collaboration 
- **Scikit-learn**: A go-to library for machine learning in Python 
- **FastAPI**: To create an ultra-fast web API to deploy our AI model 
- **Joblib**: To save and reload our trained model 
- **Uvicorn**: The lightning-fast ASGI server for running FastAPI 
- **Pandas**: For all things data manipulation 
- **MLflow**: For track experiments, log models, and manage model versions. 

---

## Get Started

Follow these simple steps to get the project up and running locally:

### 1. Clone the repository:
Start by cloning the repository to your local machine:

```bash
git clone https://github.com/Lody7/Homework_MLFlow.git
cd Homework_MLFlow
```

###  2. Install the required dependencies:
```bash
pip install -r Requirment_install.txt
```

### 3. Train the model:
Run the Python script to train the customer churn model and save it to a `.pkl` file:

```bash
cd modeling
python train.py
```

### 4. MLflow Experiment Tracking

#### API Endpoints
Start MLflow UI:

```bash
mlflow ui
```

Access the MLflow UI at: http://127.0.0.1:5000

###  5. Start the FastAPI server:
```bash
uvicorn main:app --reload
```

### 6. To make predictions, send a POST request to `/predict` with the customer data in JSON format.

#### API Endpoints

- **POST /predict**: Predict customer churn based on the input data.

    Example request:
API