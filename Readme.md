AutoAI Model Building in IBM Watson Studio
This project demonstrates how to build a machine learning model using IBM Watson Studio's AutoAI tool. The goal of the model is to predict PM2.5 levels (a key air pollution indicator) based on various environmental features such as PM10, NO2, SO2, CO, O3, temperature, humidity, and wind speed.

🚀 Project Objective
To predict PM2.5 (fine particulate matter) levels in air using machine learning with AutoAI in Watsonx.ai.

Implementation Steps
Uploaded and cleaned air quality dataset.
Used IBM Watsonx's AutoAI to automatically build machine learning pipelines.
Selected the best performing model pipeline.
Deployed the model as an API endpoint.
Used a test dataset to validate the deployed model via a REST API call.

Tools & Technologies
IBM Watson Studio (AutoAI)
Python
REST API
pandas
requests

Sample Prediction Output
The model takes inputs like:

<img width="1055" height="280" alt="image" src="https://github.com/user-attachments/assets/65fa02cd-0d27-467e-af15-d65267bc855e" />
