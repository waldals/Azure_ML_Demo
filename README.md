# Azure Machine Learning Studio Demo

# Project Description
This is a repository to hold code related to an Azure Machine Learning Studio Demo working with a toy dataset and RandomForestRegressor to predict the Average Price of avocados.

## Useful Links
[This Repo](https://github.com/waldals/Azure_ML_Demo)  
[Azure Machine Learning Studio help](https://docs.microsoft.com/en-us/previous-versions/azure/machine-learning/studio-module-reference/)  

## Contact Info
- Stacey McLennan-Waldal, Data Scientist (Stacey.Waldal@gmail.com)

## Repository Organization
```
Azure_ML_Demo
│   readme.md                                 this readme
│   requirements.txt                          .txt file for setting up conda 
│   PySpark_SQL_Cheat_Sheet_Python.pdf        reference document for writing in pyspark
│   
└───data				folder for data files
│	│	└ avocado.csv 			.csv file of data for this demo
│
└───notebooks				folder for different file types to run code
│	│	└ Azure_ML.dbc 			.dbc file for use in DataBricks
│	│	└ Azure_ML_html.zip 			.zip file to view code in HTML/browser
│	│	└ Azure_ML_python.zip 			.zip file for use in IDE (i.e. Jupyter)
│
└───includes			folder containing supplemental notebooks to run Avocados
│	└─── configuration			notebook to configure packages 
│	└─── main			general tasks folder
│	│	└─── python			folder containing supplemental functions to run Avocados
│	│	│	└ operations			notebook containing supporting functions to run model, predictions, and view results
```

## Summary
**Goals of this work was to:**
1.	Predict Average Price of avocados using historic data.
2.	Build an accurate prediction model.
3.	Translate code-approach into Azure ML Design Studio pipeline.

**Results:**
1.	RandomForest regressor model built to predict Average Price of avocados with an understanding of important features that influence the price.
2.	Pipeline recreated the workflow with a no-code approach.

# Setting Up Data For This Project
1. ensure the data is available and loaded into DataBricks dbfs if using .dbc file.

# Setting Up Local IDE & Project Workspace
1. clone this repository to a local workspace
2. set up a conda virtual environment for this project, install requirements.txt
3. run data notebooks to create the required dataset or connect to data already available
4. run notebooks within folder of interest

# How To Use Repository
1. ensure the data is available and loaded into DataBricks dbfs if using .dbc file.
2. select version of Avocado file to use/run; multiple file types loaded in repository.
3. run configuration and operations supplemental files.