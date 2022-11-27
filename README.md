# Intro. to Machine Learning Final Project (ECGR 4105/5105)
Summary:
For this following project, the project will use the Brain Tumor MRI Dataset to do image
classification over multiple different classifier’s algorithms. The classifier’s algorithms
aim to process at least three algorithms: Logistic Regression, Naïve Bayes, Support
Vector Machine (SVM) or Convolutional Neural Network (CNN). The analysis of this
project is to identify which of the algorithms give the most accurate predictions among
four classes of the brain tumor with the dataset of MRI images. Disclaimer for this
following project, the project is aimed to compare the accuracy alongside multiple
classifiers and would require more testing to be applicable for real-world applications. 

Brain Tumor MRI Dataset: https://doi.org/10.34740/KAGGLE/DSV/2645886

Simple color classification and dataset was added to be used as an control group and comparison
between other classifiers. 

Color Dataset: https://doi.org/10.34740/KAGGLE/DSV/28939

Convolutional Nerual Network (CNN):

Supported Vector Machine (SVM) and Logistic Regression:
The images were imported into the notebook and sample images with the provided classes' category
was provided. The images had to be resized and converted into data array (matrix) and then insert
into the data table. The data of arrays will be reshaped for cleaner data table to be process into
the classifier. Since the Brain Tumor provided a training and testing sets, they will be splitted 
accordingly. The data table was featured scaled (standardization) and extracted/combined (PCA extraction)
reduces the runtime. Graphs of the precision, recall and accuracy over the numbers of PCA extraction
is provided for analysis. 