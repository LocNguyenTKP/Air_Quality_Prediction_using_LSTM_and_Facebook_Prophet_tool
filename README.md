![image](https://github.com/LocNguyenTKP/Air_Quality_Prediction_using_LSTM_and_Facebook-s_Prophet_tool/assets/66542803/41e36239-2c1e-4ad8-857e-d8e582bbbcdd)

# Air_Quality_Prediction_using_LSTM_and_Facebook_Prophet_tool 

## Introduction
This repository uses an advanced Air Quality Prediction Model designed to help cities breathe easier :). Leveraging advanced Deep Learning models of LSTM (Long Short-Term Memory) networks and the intuitive capabilities of Facebook's Prophet tool. Air quality is a crucial environmental issue that impacts health, economic activity, and ecological balance. This model aims to forecast air quality accurately, enabling timely interventions for healthier urban living.

## Methodology
The model began with thorough data exploration, where we delved into historical air quality metrics to understand patterns and key indicators. By training and testing the LSTM model on this rich dataset, and the predictive power of Prophet, I've developed a tool that not only forecasts but also adapts to seasonal and unexpected changes in air quality.

## Implementation Steps
### 1. Data Handling and Visualization:
The notebook starts with loading air quality data and performing basic data descriptions and preprocessing.
It includes visualization of air quality data, such as plotting PM2.5 levels across different time frames—yearly, monthly, daily, and hourly using box plots and line plots to analyze trends and outliers.
![image](https://github.com/LocNguyenTKP/Air_Quality_Prediction_using_LSTM_and_Facebook-s_Prophet_tool/assets/66542803/0ca5ea3c-dc7f-4ec7-88a8-d776e7c9f41a)

### 2. Data Preparation:
The data is preprocessed for the neural network model, including handling timestamp data, creating new columns based on time (like year, month, day, hour), and scaling the data using MinMaxScaler.
![image](https://github.com/LocNguyenTKP/Air_Quality_Prediction_using_LSTM_and_Facebook-s_Prophet_tool/assets/66542803/29f87d17-bed8-4e75-a13a-005a56c9981a)
![image](https://github.com/LocNguyenTKP/Air_Quality_Prediction_using_LSTM_and_Facebook-s_Prophet_tool/assets/66542803/f7194fc8-0751-4894-8b5d-4419eedcaf74)
![image](https://github.com/LocNguyenTKP/Air_Quality_Prediction_using_LSTM_and_Facebook-s_Prophet_tool/assets/66542803/b2837a24-9f09-4f95-938c-50f4fc0a95a6)

### 3. LSTM Model Building:
An LSTM model is constructed and trained to predict future PM2.5 levels. This includes splitting the data into training and test sets, configuring the LSTM layers, and compiling the model with loss and optimization parameters.
### 3.1 Model Training and Prediction:
The model is trained with the prepared data and then used to make predictions. The results are then visualized by comparing the predicted values against the actual values in the test data.
![image](https://github.com/LocNguyenTKP/Air_Quality_Prediction_using_LSTM_and_Facebook-s_Prophet_tool/assets/66542803/7251e600-3f34-4ac5-9b87-d4b06483eeb2)

### 3.2 Evaluation LSTM Model:
Performance metrics such as mean squared error, mean absolute error, and R^2 score are calculated to evaluate the model’s accuracy.
![image](https://github.com/LocNguyenTKP/Air_Quality_Prediction_using_LSTM_and_Facebook-s_Prophet_tool/assets/66542803/636d6afa-25b6-4609-bd83-5bb84a7b21fb)
![image](https://github.com/LocNguyenTKP/Air_Quality_Prediction_using_LSTM_and_Facebook-s_Prophet_tool/assets/66542803/d0946355-60dc-4fde-a1d5-cfd714fe4787)
![image](https://github.com/LocNguyenTKP/Air_Quality_Prediction_using_LSTM_and_Facebook-s_Prophet_tool/assets/66542803/e58abb5c-64c1-41c5-96f1-cc49a1b7b3cb)

### 4. Prophet for Forecasting:
### 4.1 Setting model:
Additionally, the notebook explores using Facebook's Prophet tool for forecasting, suggesting a comparative approach to modeling time series data.
![image](https://github.com/LocNguyenTKP/Air_Quality_Prediction_using_LSTM_and_Facebook-s_Prophet_tool/assets/66542803/3613fec7-b536-4133-8cb3-2185cf166322)

### 4.2 Visualization of Results:
The results of the predictions and forecasts are plotted to visualize the model's performance over time, comparing predicted values with actual data.
![image](https://github.com/LocNguyenTKP/Air_Quality_Prediction_using_LSTM_and_Facebook-s_Prophet_tool/assets/66542803/369feafd-13d8-4421-8e16-e2b00658e0c6)

## Contributing
Contributions to this project are welcome. Please fork the repository and submit a pull request with your suggested changes.

## Contact
For any queries or further collaboration, feel free to contact Loc Nguyen nguyenloctkp@gmail.com.
