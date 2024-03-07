# ML_Pipeline_Airfoil_Noise_Prediction

This Coursera project is from the course: Machine Learning with Apache Spark, which is a part of the 13 course series: IBM Data Engineering Professional Certificate.

In this project, you will work with the modified version of the NASA Airfoil Self Noise dataset.

The goal of this project is to practice the skills of data engineering, specifically to clean the dataset, create a Machine Learning pipeline, evaluate the model's performance, and persist it for future use. 

### Scenario
You are a data engineer at an aeronautics consulting company. Your company prides itself in being able to efficiently design airfoils for use in planes and sports cars. Data scientists in your office need to work with different algorithms and data in different formats. While they are good at Machine Learning, they count on you to be able to do ETL jobs and build ML pipelines. In this project you will use the modified version of the NASA Airfoil Self Noise dataset. You will clean this dataset, by dropping the duplicate rows, and removing the rows with null values. You will create an ML pipe line to create a model that will predict the SoundLevel based on all the other columns. You will evaluate the model and towards the end you will persist the model.

### Objectives
In this 4 part assignment you will:

Part 1. Perform ETL activity: You will begin by cleaning the dataset and removing duplicate rows and rows with null values. Doing this step ensures the data is consistent and reliable for further analysis 
- Load a csv dataset
- Remove duplicates if any
- Drop rows with null values if any
- Make transformations
- Store the cleaned data in parquet format
  
Part 2. Create a Machine Learning Pipeline: Next, you will construct a Machine Learning pipeline with three stages, including a regression stage. This pipeline will enable you to build a model that predicts the SoundLevel based on other columns in the dataset 
- Create a machine learning pipeline for prediction
  
Part 3. Evaluate the Model: Once you’ve trained the model, you will evaluate its performance using appropriate metrics to assess its accuracy and effectiveness 
- Evaluate the model using relevant metrics
  
Part 4. Persist the Model: Finally, you will persist with the model, saving it for future use. This step ensures that the trained model can be stored and retrieved later, enabling its deployment in real-world applications and making predictions on new data
- Save the model for future production use
- Load and verify the stored model

### Datasets
In this lab you will be using dataset(s):

- The original dataset can be found here NASA airfoil self noise dataset. https://archive.ics.uci.edu/dataset/291/airfoil+self+noise
- This dataset is licensed under a Creative Commons Attribution 4.0 International (CC BY 4.0) license.
