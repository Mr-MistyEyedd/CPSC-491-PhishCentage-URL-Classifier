# CPSC-491-PhishCentage-URL-Classifier
 This is a semester project for CPSC 491: Senior Capstone Project in Computer Science. The objective of this project is to employ machine learning techniques in the field of cybersecurity with the aim of developing a classifier system capable of distinguishing between legitimate and malicious URLs.


## Datasets Used:
NOTE: Raw dataset files are not included in this repository, as it is too large to commit. However, you can download these data sets in the links below and place these files in the `/Dataset` folder before running these notebooks.

 - Dataset of Malicious and Benign Webpages: https://data.mendeley.com/datasets/gdx3pkwp47/1
 - 7+ Million Company Dataset: https://www.kaggle.com/datasets/peopledatalabssf/free-7-million-company-dataset?resource=download 

## Machine Learning Algorithms: 

 This project utilizes 4 machine learning algorithms: K-Nearest Neighbors, Decision Trees, Random Forests, and Naive Bayes. Each model was trained on the Dataset of Malicious and Benign Webpages (See above) both trained on full and reduced feature sets, creating a total of 8 models. All 8 models have been combined together to perform hard classification (Classifying based on majority votes).

 So far, these are the results when measuring this system based on accuracy, precision, recall, F1-Score, and AUC:

![Result](https://github.com/Mr-MistyEyedd/CPSC-491-PhishCentage-URL-Classifier/blob/main/Figure%2014.png)



## Technologies Used: 

<p align="left">

<img src="https://img.shields.io/badge/Jupyter-F37626.svg?&style=for-the-badge&logo=Jupyter&logoColor=white" alt="html" style="vertical-align:top; margin:3px">
<img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" alt="html" style="vertical-align:top; margin:3px">
<img src="https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" alt="html" style="vertical-align:top; margin:3px">
<img src="https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white" alt="html" style="vertical-align:top; margin:3px">
<img src="https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white" alt="html" style="vertical-align:top; margin:3px">
<img src="https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white" alt="html" style="vertical-align:top; margin:3px">
<img src="https://img.shields.io/badge/LaTeX-47A141?style=for-the-badge&logo=LaTeX&logoColor=white" alt="html" style="vertical-align:top; margin:3px">


</p>
