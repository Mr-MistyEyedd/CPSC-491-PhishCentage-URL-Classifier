# CPSC-491-PhishCentage-URL-Classifier
 This is a semester project for CPSC 491: Senior Capstone Project in Computer Science. The objective of this project is to employ machine learning techniques in the field of cybersecurity to develop a classifier system capable of distinguishing between legitimate and malicious URLs.

# Function
 This project was created using the Jupyter Notebook software in a Python version 3.12 Virtual Environment. Make sure to install the necessary modules beforehand for the cells to function correctly when run. Some of the Jupyter files have a couple of instructions or texts that describe what was done to the Virtual Environment in order to assist the user. If the instructions are too vague, research the solutions of the error messages if they are given after the cells are run. 

## Datasets Used:
NOTE: Raw dataset files are not included in this repository, as it is too large to commit. However, you can download these data sets in the links below and place these files in the `/Dataset` folder before running these notebooks.

 - Dataset of Malicious and Benign Webpages: https://data.mendeley.com/datasets/gdx3pkwp47/1
 - 7+ Million Company Dataset: https://www.kaggle.com/datasets/peopledatalabssf/free-7-million-company-dataset?resource=download 

## Machine Learning Algorithms: 

 This project utilizes 4 machine learning algorithms: K-Nearest Neighbors, Decision Trees, Random Forests, and Naive Bayes. Each model was trained on the Dataset of Malicious and Benign Webpages (See above) both trained on full and reduced feature sets, creating a total of 8 models. All 8 models have been combined together to perform hard classification (Classifying based on majority votes).

 So far, these are the results when measuring this system based on accuracy, precision, recall, F1-Score, and AUC:

![Result](https://github.com/Mr-MistyEyedd/CPSC-491-PhishCentage-URL-Classifier/blob/main/Figure%2014.png)



## Technologies Used: 

Jupyter Notebook
Python 3.12
Scikit Learn
Numpy
Pandas
Graphviz
