# INSTRUCTIONS FOR USING MODELS

## Pre-processing Transport
- We have taken data from the given sources. (you can get the files for same in the drive link attached at the end of README.md file -> after downloading the folder , 2. create a folder with name 'transport' on the google collab files and upload the files there -> After creating the folder, copy the path, and past it in required cell).
- A loop runs on the combine dataFrame to get number of diesel cars sold in a day. 
- After running the cells one can get a data profiling document and a csv file called 'transport'. 
(Note - no. of diesel cars are taken in consideration as increase in no of diesel cars on road increases the chances of heatwave)

## Heat Wave occurrence
- Download the file 'temp34.csv' from the Github and upload it in content of Google Collab -> Copy its path and paste it in df0
- Copy the transport.csv 's path from content and paste it in df2
- After running the cells, one will get prediction through LSTM Model

## AQI Prediction
- Download 'AQI.csv' from the Github and upload it in content of Google Colab-> copy its path and past in the required cell
- In EDA, it was found that PM10 is highly correlated to AQI with correlation coefficient =0.85. This it has been taken into consideration while building the model
- Decision Tree Regressor is used for predicting the AQI for the next month

(Note - In the code, we have used only 1 district to showcase the model proficiency.
Same codes and model can be used for other districts by just replacing the district name in the cell according to choice)
(google drive - https://drive.google.com/drive/folders/1siMdX-Do3rmcg1TIFpYvmT1QfWHx1dFp?usp=share_link)



# 83ef369f-ab52-4f2b-b47c-7b0b19ac70ca
https://sonarcloud.io/summary/overall?id=examly-test_83ef369f-ab52-4f2b-b47c-7b0b19ac70ca
