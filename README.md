# End to End Machine Learning Project : Student_Performance_App

![alt text](StudentPerformanceApp.jpg)


📊 Student Performance App Workflow
Data Collection & Preprocessing

Source: Raw student performance data is collected and stored in the notebook/ directory.

Processing: Data cleaning, feature engineering, and exploratory data analysis are performed using Jupyter Notebooks.

Model Training

Algorithm: A machine learning model, likely using CatBoost (as indicated by the catboost_info/ directory), is trained on the preprocessed data.

Artifacts: Trained model artifacts are saved in the artifacts/ directory for later use.

Application Backend

Framework: The backend is developed using Flask, as suggested by the presence of app.py.

Functionality: Handles HTTP requests, loads the trained model, and processes user inputs to generate predictions.

Frontend Interface

Templates: HTML templates located in the templates/ directory provide the user interface.

User Interaction: Users input data through web forms, which are then sent to the backend for prediction.

Deployment

Containerization: A Dockerfile is present, indicating that the application is containerized using Docker.

Cloud Deployment: The .ebextensions/ directory suggests deployment on AWS Elastic Beanstalk.

Automation & CI/CD

GitHub Actions: Workflows defined in .github/workflows/ automate tasks such as testing, building, and deploying the application.

