# CPSC-491-PhishCentage-URL-Classifier
 This is a semester project for CPSC 491: Senior Capstone Project in Computer Science. The objective of this project is to leverage machine learning techniques within cybersecurity to create a classifier capable of identifying and distinguishing between legitimate and malicious URLs.

# Requirements
 This project was created using the Jupyter Notebook software in a Python version 3.12 Virtual Environment. Make sure to install the necessary modules beforehand for the cells to function correctly when run. Some of the Jupyter files have a couple of instructions or texts that describe what was done to the Virtual Environment in order to assist the user. If the instructions are too vague, research the solutions to the error messages if they are given after the cells are run. 

## Datasets Used:
NOTE: The raw dataset files are not included in this repository, since it is too large to commit. You can download these data sets in the links below and place these files in the `/Dataset` folder before running these notebooks instead.

 - Dataset of Malicious and Benign Webpages: https://data.mendeley.com/datasets/gdx3pkwp47/1
 - 7+ Million Company Dataset: https://www.kaggle.com/datasets/peopledatalabssf/free-7-million-company-dataset?resource=download 

## Machine Learning Algorithms: 

 This project utilizes 4 machine learning algorithms: K-Nearest Neighbors, Decision Trees, Random Forests, and Naive Bayes. All four of the models were trained on the Dataset of Malicious and Benign Webpages (Links above) both trained on full and reduced feature sets, creating a total of 8 models. Those 8 models were combined to perform hard classification (Classifying based on majority votes).

 So far, these are the results when measuring this system based on accuracy, precision, recall, F1-Score, and AUC:

![Result](https://github.com/Mr-MistyEyedd/CPSC-491-PhishCentage-URL-Classifier/blob/main/Figure%2014.png)



## Technologies Used: 

Jupyter Notebook, 
Python 3.12, 
Scikit Learn, 
Numpy, 
Pandas, 
Graphviz
