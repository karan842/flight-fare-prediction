# Indian Flight Fare Prediction WEB-APP✈️🎟️

App: https://air-fare-india.herokuapp.com

Machine Learning based web-app which can predict the Price of flight fare (aprroximately). Taking inputs those are
1. Departure Time
2. Arrival Time
3. Source
4. Destination
5. Stop-page
6. Airline (only India)

# About Project:
  This is a end to end Data Science project where the task is to predict the Fare of the flights (Indian Only). Data is in the form of Excel spreadsheets, one is for training purpose and  the other is for testing.

- There are four main tasks 
  1. Data cleaning, preprocessing and Visualization (Data Analytics)
  2. Building Machine Learning Model with model evaluation
  3. Create a web app which can predict the Price
  4. Make this web app available on PCs and phones.
 
 # Approcach:
      
- Collected spreadsheets from **Kaggle**
- There are two spreadsheets - Training and Testing
- I created two notebooks 
    1. flightFare.ipynb for Data Analytics
    2. modelTraining.ipynb for Machine Learning
- First notebook: 
      Imported essential libraries and analyzed the main features from the data. Worked on missing values, labelencoding and visualization on both training and testing data.
                  Saved those processed data and saved them.
                  
- Second Notebook: 
        Imported preprocessed data and splitted into train and test datasets. Started selecting theri features by ExtraTreeRegressor which predicted the important factors and visualized those important factors and found correlation by heatmap.
                   For this task I used two ML algorithms **RandomForestRegressor** and **XGBRegressor**. Predicted both model's score on on train and test datasets. Evaluated both models by **MSE**, **MAE** and **RMSE**.
                   To get better accuracy I performed Hyperparameter Tunning i.e. **GridSeachCV** and **RandomizedSearchCV** on XGBRegressor and RandomForestRegressor respectively. Evaluated both models and choosed the best one with higher accuracy.
                   exported better model(**XGBRegressor**).
                   
- Flask App: Created a flask app as a backend and created frotnend by simple HTML and CSS.
- Pushed this project on GitHub
- Deployed the model on **Heroku**

# Thank You🪄🙋🏽‍♂️
