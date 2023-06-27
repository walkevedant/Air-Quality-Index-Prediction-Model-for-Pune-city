# Pune City Air Quality Index Prediction using Machine Learning
This project focuses on predicting the Air Quality Index (AQI) in Pune City, India, using machine learning techniques. The AQI is an important indicator of air pollution levels, and accurate predictions can help raise awareness, inform decision-making, and facilitate effective pollution control measures. The project utilizes a dataset containing historical air quality data and various environmental parameters.

Project Steps:

* Data Preparation:
 The project begins by loading the air quality dataset from the file "AQI_Report Data for year 2021.csv" using the Pandas library.
The unnecessary columns and missing data are removed from the dataset.
The dataset is then preprocessed and saved as "aqidata.csv" for further analysis.

* Data Analysis and Model Development:
The preprocessed dataset is loaded and analyzed using Pandas and NumPy libraries.
The dataset is split into input features (x_data) and the target variable (y_data).
A machine learning model is constructed using PyTorch, specifically a neural network model with multiple linear layers and ReLU activation functions.
The model is trained using the mean squared error (MSE) loss function and the Adam optimizer.
The training process involves iterating through multiple epochs, with periodic updates on the loss value.
The loss values are recorded to track the model's learning progress.

* Model Evaluation:
The trained model is saved as "aqidatamodel.pth" for future use.
A subset of the dataset is selected as the test data for model evaluation.
The model is used to predict the AQI for the test data.
The predicted AQI values are compared with the actual values to calculate the loss.
The loss value is visualized using matplotlib to assess the model's performance.
* Conclusion:
In conclusion, this project aims to predict the Air Quality Index in Pune City using machine learning techniques. By analyzing historical air quality data and environmental parameters, a neural network model is trained to make accurate predictions. The model can be utilized to forecast the AQI, helping authorities and individuals take proactive measures to mitigate air pollution and protect public health. The project's code and documentation can be found on GitHub, enabling others to understand and reproduce the results, contribute to further improvements, and promote open collaboration in addressing air pollution challenges.
