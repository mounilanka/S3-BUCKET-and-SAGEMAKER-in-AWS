# S3-BUCKET-and-SAGEMAKER-in-AWS
DATASET :train-1.csv
         test-2.csv
ENVIRONMENT: AWS -Sagemaker-S3 bucket-Notebook Instance-Jupyter Notebook
 Import Libraries:
   import pandas as pd
   import boto3
   import numpy as np
   import matplotlib.pyplot as plt
   import seaborn as sns
   from sklearn.datasets import load_boston
   
 step1: Importing necessary Libraries
 step2:Creating S3 bucket
  step3:Mapping train And Test Data in S3
  step4:Mapping The path of the models in S3
 step5:Data Visualization
 step4: Data cleaning 
 step5: Converting Categorical Features
 step6: Building a random forest classifier model to splitting our data into a training set 
 step7:Training ,predicting and Evaluation
