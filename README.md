
# Heart Failure Prediction


## Description
Welcome to the Heart Failure Prediction project! In this exercise, we delve into a comprehensive analysis of the Heart Failure Predictions dataset sourced from Kaggle. The primary objective is to develop a predictive model for heart failure based on a set of features.

## Instructions

* **Download the Dataset**: Begin by downloading the Heart Failure Predictions dataset from Kaggle using the provided link: [Heart Failure Predictions Dataset](https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction).

* **Data Normalization**: Check the initial normalization status of the input data. If necessary, perform appropriate data normalization to ensure consistent scaling across features.

* **Feature Correlation Analysis**: Investigate the correlation between various features in the dataset. This step will provide insights into potential relationships and dependencies among the features.

* **Dataset Splitting**: Split the dataset into three subsets: training, testing, and validation. This division is essential for developing a robust and accurate predictive model.

* **Logistic Regression Estimation and Regularization Path Plotting**: Utilize logistic regression to estimate the model and generate a visualization of the regularization path. Analyze the plot to draw meaningful conclusions about the model's behavior.

* **Optimal L2 Regularization**: Determine the optimal value of the L2 regularization parameter using the validation set. This step helps in fine-tuning the model's performance.

* **Test Error Calculation**: Calculate the test error of the model using the separate test dataset. This metric indicates how well the model generalizes to new, unseen data.

## Dataset Description
* Age: age of the patient [years]
* Sex: sex of the patient [M: Male, F: Female]
* ChestPainType: chest pain type [TA: Typical Angina, ATA: Atypical Angina, NAP: Non-Anginal Pain, ASY: Asymptomatic]
* RestingBP: resting blood pressure [mm Hg]
* Cholesterol: serum cholesterol [mm/dl]
* FastingBS: fasting blood sugar [1: if FastingBS > 120 mg/dl, 0: otherwise]
* RestingECG: resting electrocardiogram results [Normal: Normal, ST: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV), LVH: showing probable or definite left ventricular hypertrophy by Estes' criteria]
* MaxHR: maximum heart rate achieved [Numeric value between 60 and 202]
* ExerciseAngina: exercise-induced angina [Y: Yes, N: No]
* Oldpeak: oldpeak = ST [Numeric value measured in depression]
* ST_Slope: the slope of the peak exercise ST segment [Up: upsloping, Flat: flat, Down: downsloping]
* HeartDisease: output class [1: heart disease, 0: Normal]