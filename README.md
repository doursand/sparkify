# sparkify
using spark and machine learning to predict users churn

### Summary
This is the Capstone project for the Udacity Data Scientist nanodegree
In this project one needs to analyse a tiny subset representation of a much larger spark dataset (12 Gb) containing information about users behaviours of a music streaming app/service (Sparkify)
The small dataset version contains only 2 months of logs
The ultimate goal is to identify which parameters are the most likely to conduct the users to churn / leave the service

### Medium publication link
https://medium.com/@andre.dourson/predict-churn-for-sparkify-app-playing-with-spark-ml-511df6c3eb35

### Requirements
This project requires the following python libraries

- pyspark
- pandas
- Matplotlib
- Seaborn
- jupyter notebook

### Files Description
- Sparkify.html	: html version of the jupyter notebook
- Sparkify.ipynb	: jupyter notebook
- dt_bestmodel.model	: export of the trained decision tree model
- mini_sparkify_event_data.json : sparkify dataset

### Result

In a nutshell, the elapsed time since the user joined is apparently playing a critical role in its decision to churn.
The machine learning model is also confirming our assumptions for churn, i.e. that user churn is mainly influenced by the amount of 'Thumbs down' and the amount of advertisement proposed to the user during its usage of the app.

Detailed results are described in the jupyter notebook attached to this repo

### Licensing, Authors, Acknowledgements
All credits go to Udacity for setting up this study
