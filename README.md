# Medical Insurance Cost Prediction Using Machine Learning

## Summary:
- A health insurance policy minimizes the expenses of losses incurred by an individual due to various hazards. Healthcare cost forecasting is a valuable tool for improving the healthcare accountability. Predicting the health insurance costs still remains as a problem in the healthcare industry that needs to be constantly investigated and improved.

- This model predicts the health insurance cost incurred by individuals based on their age, gender, Body Mass Index (BMI), number of children, smoking habits and their geo-location. Using the pandas library,  the dataset is imported and the descriptive statistics is obtained. Using matplotlib and seaborn libraries, the data is visually understood and the key attributes are fetched which are essential for determining the insurance charges. The attributes are fed into various regression models like Linear Regression (LR), Support Vector Regression (SVR), Random Forest Regressor (RFR), Stochastic Gradient Boosting (SGB) and evaluated on the basis of metrics score to select the best model among them. Then a new data value is given for the selected model to predict the insurance cost. In order to improve the performance of traditional approaches, the ensemble learning methods are used.

- Estimating accurate insurance charges benefits the health organizations and the insurers by letting them know the charges that can be incurred in future. It helps them to choose insurance plans with appropriate premiums. These elements play a important role in the development of insurance policies.

 ## Software Components
 - Jupyter Notebook
 - Libraries
   - Numpy
   - Pandas
   - Matplotlib
   - Sklearn
   - Seaborn
   - joblib
   - tkinter

## Steps for implementation:
1) Data Collection  
   - Collecting required data  
   - Loading required libraries
     
2) Data Preparation  
   - Data Cleaning  
   - Data Normalization  
   - Categorical Data Encoding  
   - Data Analysis  
   - Splitting the data
      
3) Model Training    

4) Model Evaluation and Validation   
   - Graphical Representation of the predicted values  
   - Metrics Evaluation  
   - Prediction using new data
         
5) Model Deployment  
   - Deploying a model is a method of implementing a machine learning model to real use. In this model, the Tkinter library is used to develop a Graphical User Interface where the users give the necessary inputs required for the prediction.
  
![image](https://github.com/ujwalapentela/Medical-Insurance-Cost-Prediction-Using-Machine-Learning/assets/69097559/b4450e3e-6ab2-49c7-94b5-0e83e950d69b)


   - Also, you can use Streamlit as a faster option to build a web app for the model. Follow the code in `HealthInsurance.py`.   
     ### Steps to run the web app:
        - Open the Command Prompt.
        - Navigate to the directory where the file is saved.
        - Run the following command to display the web app in your browser.
            `streamlit run HealthInsurance.py`
     








   

   
 

 

 

