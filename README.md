# **Covid-19 Cases Predictions in Malaysia by Forecasting Time Series Model using LSTM 📈📉**

This LSTM neural network model was trained using nearly 1500 raw datasets to forecast the new cases for Covid-19 in Malaysia.

## **Descriptions:**
1. **_Objective_**: To predict new cases in Malaysia using the past 30 days of number of cases in order to determine if travel bans should be imposed or rescinded.
2. The datasets are officially provided by **Ministry of Health Malaysia (MOH)**.
3. The dataset contains anomalies as 2 different type of NaNs with 10 duplicates data.
4. The layers used in the model training are input layers, LSTM and Dense as the output. A

### *Model Architecture:*
![model](https://github.com/user-attachments/assets/73d17436-fe60-48ff-b935-c321cf691e95)

## **Results:**  

### *Model Score Evaluation:-*
![result_evaluation](https://github.com/user-attachments/assets/e4f1bfeb-ed24-4da6-a809-00c0877f425f)

### *Trend Predictions for Covid-19 New Cases in Malaysia:-*
![Prediction_graph](https://github.com/user-attachments/assets/02478254-f099-493b-8cc4-7fa7383adff2)

## **Discussions:**
1. The model able to predict the trend of the Covid-19 cases in Malaysia.
2. Only LSTM, Dense, and Dropout layers had been implemented in this model.
3. Nodes in the LSTM layers were 32 and 64, and the activation used in this model was tanh.
4. Window size that set in this model was up to 30 days.
5. From the result can be seen that the MAPE error was 0.09% which lesser than 1% during the evaluation and by using test dataset.
6. For MAE evaluation, the loss for the model only 0.0025.
7. The training loss able to diplay using TensorBoard as below:
   
### *Training Loss:-*

![training_loss](https://github.com/user-attachments/assets/2c7cb7a2-329b-4c92-a638-37e2adc96dfa)

### *Training Mae:-*

![training_mae (2)](https://github.com/user-attachments/assets/6bd66910-97d7-4894-8cd2-89c64bf9ef2e)


## **Credit:**
The source of the dataset are 100% from MoH Malaysia.
Check out for the latest dataset from their GitHub just one click away 😇 :  
[Github MoH](https://github.com/MoH-Malaysia/covid19-public/tree/main/epidemic)
