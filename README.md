# Stock_Predictor_App
Streamlit App for Predicting Stock Prices using historical data
/****************************************************************************************************************************/
A LSTM (Long short term memory) model trained on the dataset fetched from yfinance (Yahoo finance) to predict the stock prices. The Stock_Prediction_App.ipynb file contains the source code for model creation, training and testing. The trained model is saved into the files stock_model.keras and stock_model.h5 (content of both the files are same but is used according to the convenience, that is, only one is used at a time), here for the App depoyment I'm using h5 format. Finally all the source code for the graphs, tables and loading the model is saved into the file Stock_Predict_App.py . Here, I have used streamlit to deploy the app which provides seamless integration from the Github repo to the App. Datas from the 2010 till present is fetch into the model.
/******************************************************************************************************************************/
To use the model, first go to the website link, the app will open with SBI's (State Bank of India) stock prediction as default, now go to the YahooFinance.com and copy the stock ticker of the stock you want to see the prediction for (Stock ticker is usually found beside the name of the stock: eg- for SBI: SBIN.NS is the stock ticker). Finally 
paste the ticker into the app and press enter, the app will load for a while and finally will display the result.
/****************************************************************************************************************************/
IF THE LINK OF THE WEBSITE DOES NOT WORK YOU CAN CONTACT ME ON MY SOCIALS, I CAN SEND YOU A CUSTOMIZED LINK.
/***************************************************************************************************************************/
NOTE: THE WEBSITE IS ONLY FOR EDUCATIONAL AND PROJECT PURPOSE AND DOES NOT GUARANTEE COMMERCIAL SUCCESS.
