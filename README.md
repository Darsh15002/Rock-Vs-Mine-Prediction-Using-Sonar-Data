# Rock-Vs-Mine-Prediction-Using-Sonar-Data
This project accurately predicts using the sonar data weather the underwater object outside the Submarine is a Rock or a Mine.

# Project Overview
Sonar stands for Sound Navigation and Ranging. It used mainly by ships, submarines and other types of marine vehicles for exploring and mapping the sound waves travelling in the water. A sonar device acts as both the sender and the receiver of the signal. The sonar device sends out ultrasound waves and detect the waves after they reflect back from underwater objects. This method is used because the sound waves travel much farther than the radar and the light waves. The distance of underwater can be calculated with the help of speed of sound in the water and the time it takes to come back to the sonar device after coming in contact with underwater object. The sound waves have the capacity to travel for hundreds of miles underwater with an intensity of 140 decibels as far as 300 miles from the source.

For practical purpose the sonar data can be easily collected with the help of a sonar device, an empty metallic cylinder and a rock. In this project I have used the sonar data to build a Machine Learning Model to predict wheatear the underwater object being examined is a Rock or a Mine. For this project I have collected the Sonar Data that I downloaded from https://www.kaggle.com/code/mattcarter865/sonar-mines-vs-rocks . This dataset has 208 rows and 61 columns where 60 columns has the sonar data and the 61th column is the target column which contains the labels ‘R’ and ‘M’ where R stands for Rock and M stands for Mine. 

# Project Workflow
![Workflow Diagram](https://user-images.githubusercontent.com/74102049/161904163-4812b00c-ea57-4af9-827d-21f225f25b62.jpeg)

# Problem Highlighted

The Goal of this project is to accurately predict weather the underwater object outside the submarine is Rock or a Mine using the Sonar Data. In this project I have used the Logistic Regression Supervised Machine Learning Model to classify the object as Rock or a Mine.
During this project I have learned following things:

  •	How to apply Machine learning models and algorithms and techniques on a dataset 
  
  •	How to collect the data and Pre – process it for analysis and feeding it to the Machine learning model to get the accurate result.
  
  •	How to perform Exploratory Data Analysis (EDA) on a dataset.
  
  •	How to choose the right Machine Learning model and algorithm for a given dataset.
  
  •	How to optimize the Machine Learning Model and increase it’s accuracy and reducing the error score.
  
# Required Installations

Following installations are required in order to run the project:

•	Python 3.x

Following Libraries are used in this project:

•	Numpy

•	Pandas

•	Matplotlib.pyplot

•	Sklearn.model_selection 

•	Sklearn.linear_model

•	Sklearn.metrics

Apart from this I would also recommend to download Anaconda which contains all the pre-packaged Python Libraries and all the other necessary software such as Jupiter Notebook. I have built this entire project in Jupiter Notebook.

# Code

The entire code is provided in one file

Apart from this I have also uploaded a PDF of my Jupiter Notebook File in this Repository for a quick reference. 

# Evaluation Metrics 

In this project I have used the Accuracy Score as the evaluation score. Accuracy Score is an evaluation metrics used in the area of Machine Learning Projects used mainly to evaluate the accuracy of the classification model. It is basically the fraction of prediction that the model used in the project got right. Good Accuracy Score in the area of Machine Learning is subjective. However, in general any score greater than 70% is considered as the great model performance.

In my project:

Accuracy Score on Training Data is 83.42%

Accuracy Score on Test Data is 76.19%
