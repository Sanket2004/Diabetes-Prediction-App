
# Diabetes Prediction System

The Diabetes Prediction Web App is a user-friendly tool that allows individuals to assess their risk of having diabetes based on various input parameters. It utilizes a machine learning model trained on relevant medical data to make predictions. Here's how the app works:


Note:
The app assumes that a machine learning model has been trained on relevant data and saved as "trained_model.sav." It also relies on a pre-fitted StandardScaler saved as "scaler.pkl" to ensure consistent data preprocessing. These model and scaler files need to be prepared separately based on a trained machine learning model and data.

Overall, the Diabetes Prediction Web App provides a convenient way for users to get an initial indication of their diabetes risk based on their health information, with the understanding that it's not a substitute for professional medical evaluation.


## Features

- Number of Pregnancies: Users input the number of pregnancies.
- Glucose Level: Users input their glucose level.
- Blood Pressure Value: Users input their blood pressure value.
- Skin Thickness Value: Users input their skin thickness value.
- Insulin Level: Users input their insulin level.
- BMI (Body Mass Index) Value: Users input their BMI value.
- Diabetes Pedigree Function Value: Users input the diabetes pedigree function value.
- Age of the Person: Users input their age.


## Prediction:

After entering the required information, users click the "Diabetes Test Result" button. The app then processes the input data, scales it using a StandardScaler, and passes it through a pre-trained machine learning model. The result is displayed to the user, indicating whether the person is diabetic or not.

- If the prediction is "The person is not diabetic," it suggests that the user is likely not diabetic.
- If the prediction is "The person is diabetic," it suggests that the user may have diabetes.

## Usage:

This web app can be used by individuals who want to quickly assess their diabetes risk by providing basic health-related information. It can serve as an initial screening tool, but it's important to note that any predictions made by the app should not replace professional medical advice. Users are encouraged to consult with healthcare professionals for accurate diagnoses and guidance.
## Deployment

To deploy this project run

```bash
  streamlit run '.\Diabetes_Prediction_App.py'
```


## Screenshots

![Diabetes Prediction App](https://github.com/Sanket2004/Diabetes-Prediction-App/blob/main/Diabetes_Prediction_App.png?raw=true)


## Authors

- [@Sanket Banerjee](https://www.github.com/Sanket2004)


## Feedback

If you have any feedback, please reach out to me at sanketbanerjee.2004@gmail.com

