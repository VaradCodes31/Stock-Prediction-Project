# Stock-Prediction-Project
A **comprehensive Stock-Price prediction** project, made entirely in **Python**, fully utilizing Python and it's **multi-faceted libraries**.
Using the **yfinance** library, which contains an exhaustive list of stock prices, starting all the way back from 1950 to 2025. 
After importing and going through the available data, for ensuring maximum accuracy while prediction, shortened the time period to only use stock prices after 01-01-1990.
Then, used every data except the last 100 rows to train the model and the last 100 rows were used to test the model.
This was achieved using the Random Forest Classifier technique, imported from Scikit-learn.
Then, using Pandas, turned the available data into boolean values, checking whether the predictions made were accurate or not.
Plotting the initial findings, used the backtesting method to improve accuracy of the model.
Once again, repeating the Random Forest Classifier with new data and findings.
Improved the precision score to just above 57%.
