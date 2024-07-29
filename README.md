# telco-customer-churn-prediction-
This repository contains the source code and resources for a machine learning web application that predicts customer churn for a telecommunications company. The project leverages historical customer data to build predictive models, enabling the identification of customers who are likely to discontinue their service.

1. # PRCL-0017-Customer_Churn.ipynb
   This Jupyter Notebook contains the main data analysis and machine learning model development process for predicting customer churn. It includes data exploration, feature engineering, model training, evaluation, and possibly deployment steps.

2. # README.md 
   This file typically contains essential information about the project, including an overview, setup instructions, usage guidelines, and any other pertinent details to help users understand and contribute to the project.

3. # app.py  
   This Python script serves as the backend of the web application, built using Flask. It handles HTTP requests, interfaces with HTML files (`index.html` and `predict.html`), and manages interactions between users and the machine learning model (`model.pkl` and `preprocessor.pkl`).

4. # flag.png
   This image file serves as an indicator of churn probability within the web application's user interface. It dynamically changes color (red or green) based on the predicted likelihood that a customer will churn, providing a visual cue for users.

5. # index.html  
   This HTML file represents the main landing page or interface of the web application. It provides the structure and content that users see when they first visit the application in a web browser.

6. # model trial.code-workspace
   This file is typically specific to Visual Studio Code (VS Code) and contains workspace settings and configurations related to the development environment. It helps maintain consistency and setup preferences across different development sessions.

7. # model.pkl
   This file stores the serialized version of the trained machine learning model. It is used by `app.py` (using Flask) to load the model into memory so that it can make predictions on new data received from the web application's users.

8. **predict.html**  
   This HTML file likely represents a page or form within the web application where users input data (such as customer information) to receive predictions from the machine learning model.

9. # preprocessor.pkl
   This file contains the serialized version of the data preprocessor or feature scaler used to transform input data before feeding it into the machine learning model. It ensures consistency in data preprocessing steps between training and prediction phases.

10. # requirements.txt
    This text file lists all the Python packages and their specific versions required to run the web application and execute the machine learning model successfully. It ensures that anyone setting up the environment can install the necessary dependencies easily using `pip`.

These files collectively form the foundation of a Flask-based web application that integrates HTML interfaces (`index.html`, `predict.html`) with a machine learning model (`model.pkl`) and its preprocessing steps (`preprocessor.pkl`). The `flag.png` file dynamically reflects churn probability, aiding in user decision-making based on model predictions.
## Languages Used

-  ![HTML,CSS,JAVASCRIPT](https://progress-bar.dev/30/?title=html,css,js)
- ![Python](https://progress-bar.dev/50/?title=Python)
- ![Flask](https://progress-bar.dev/20/?title=Flask)
