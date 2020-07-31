# Amazon-Sagemaker-autoML-bank-marketing-offer

Input Data: bank-additional.csv

Upload data set to Amazon S3

Notebook Files:  mainnotebook, Open data exploration notebook, Open candidate generation notebook

Amazon Sagemaker autoML steps:
1. Analyzing Data
2. Feature Engineering
3. Model Tuning
4. Completion

After execution of autoML steps, do graphical analysis of the built models and pick up the best model using the deploy model option. Deploy a model to a SageMaker endpoint, and to send it data for prediction using the boto3 SDK. Make predictions on the test data using confusion matrix.
