# ChurnSight-Streamlined-Churn-Prediction-and-Deployment-with-Docker🔄🔮 
This project implements an interactive churn prediction application using Python, Streamlit, and Docker. The application is designed to predict customer churn in a telecom dataset using logistic regression, achieving an accuracy of 80.1% compared to a baseline of 73.8%. The model is trained using K-fold cross-validation, resulting in an AUC of 85.8%, ensuring robust performance.

## 🚀 Features:
- Interactive web interface powered by Streamlit for easy data input and prediction
- Containerized using Docker for seamless deployment and scalability
- Utilizes logistic regression for churn prediction
- K-fold cross-validation for model training and evaluation

## 🛠️ Prerequisites:

- An IDE/ Text Editor 
- Python 3.6+ 
- PIP (or Anaconda)
- Not required but recommended: An environment management tool such as pipenv, venv, virtualend, conda.
- Docker Desktop

## ⚙️ Installation:
To run the application, follow these steps:

Clone the repository: 
```
git clone [repository URL]
```

Install dependencies:
```
pip3 install -r Pipfile
```

Run the Streamlit application:
```
 python3 stream_app.py
```

## 🐳 Running the Application
Clone the repository and navigate to the project directory.

Build the Docker image
```bash
docker build -t churn-prediction-app
```

Run the Docker container, mapping the local port to the container's port (replace `XXXX` with the desired port number)
```
docker run -p XXXX:8501 churn-prediction-app
```

## 🖥️ Viewing Your Streamlit App
- Access the web interface by opening the provided URL in the Docker Container
- Input customer data such as contract length, monthly charges, etc.
- Click on the "Predict" button to see the churn prediction for the customer



<img width="769" alt="image" src="">

## 🙏 Acknowledgements
Docker Samples
