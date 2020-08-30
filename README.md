# Carprice-Prediction-CarDhekho...
Predicting the car price using ML techiques with CarDehko Data
# Project Structure

This project has three major parts :

1.app.py - This contains Flask APIs that receives car details through GUI or API calls, computes the precited value based on our model and returns it.

2.random_forest_regression_model.pkl - module is used for serializing and de-serializing python object structures 

3.requirements.txt - This text file contains the packages needed to run the model 

4.Deployment - Heroko cloud platform used 
    
 # Following are the steps involved in buiding a stable model 
  
  1. Importing the data
  
  2. Data preprocessing 
  
  3. Handling the missing values if any 
  
  4. Going on with one-hot-encoding as their are categorical data 
  
  5. Finding the correlation and multicollinearity using pairplot and heatmap
      ![Alt Text](C:\Users\koush\OneDrive\Desktop\github images)
      
  6. Creating a train and test split of the data for training the model and again testing the model with useen data(test data)
  
  7.Moving on hyperparameter tunning with randomgrid cv.
  
  8.Searching the best parameters with 3 fold cross validation
  
  9.fit the model to train and test data and predict the results 
  
  10.Subtracting the predicted and given values and finding out the model accuracy 
  
