# SBE2240 Biostatistics Final Project

## Objective

Statistics plays an essential role in analyzing the data and making a decision based on it.  In this project, you will explore different types of statistical techniques and learn how to use them to build and deploy a statistical-based Machine learning system. 

## Main Project Idea 

The main idea of the project is to select a specific dataset and use one of the supervised learning methods to build a system that's capable of predicting the class of a new data item. You're also required to deploy it using a simple web application so the end-users can use it. 


The main steps of the project: 

1. Data preprocessing and exploration 
2. Feature extraction and selection 
3. Training the ML model 
4. Testing the model 
5. Deploying the model on a web application 

## Deadline 

The deadline of the project is **Sunday 22/5/2022**

## Suggested datasets

1. Cardiovascular disease detection
    
    Classify the patients to be healthy or suffering from cardiovascular disease based on the given attributes [link](https://drive.google.com/drive/folders/10ncKH-338bcZpLnRlWnNqjy9x5K4oSCe)

2. Predict diabetes

    Build a machine learning model to accurately predict whether the patients in the dataset have diabetes or not? [link](https://drive.google.com/drive/folders/1TyRe_rpc4Jyvf8ks3znknmaEmLcqoqsw?usp=sharing)

3. Coronavirus tweets Text Classification
    
    Classify the tweets about the Coronavirus into positive, neutral, or negative tweets. [link](https://drive.google.com/drive/folders/1n6z0IwMjHAaFQgVQAVzPm4XU1VjEmAjc)

    **Note:** for feature extraction use [TFIDF](https://scikit-learn.org/stable/modules/feature_extraction.html#text-feature-extraction)
    
4. Covid Patients' Chest X-Ray images 
 
    Differentiate between covid patient lungs and normal ones.[link](https://drive.google.com/drive/folders/1IZRX1ADKuE3hcUjTXAFHOgSoWVo54tU9)

    **Note:** for feature extraction use [HOG](https://scikit-image.org/docs/dev/auto_examples/features_detection/plot_hog.html)
    

## Other Datasets

You can select any other dataset and it isn't necessary to be a medical dataset but you should inform the TA and get his confirmation. 


## Allowed Classifiers

1. Multinomial Naive Bayes Classifier 
2. Supported Vector Machine Classifier (SVM)
3. Decision Tree Classifier  
4. Random Forest 
5. Multi-layer Perceptron (MLP)
6. KNearest Neighbors Classifier (KNN)

## General Rules 

* Each team should use only one dataset and one classifier so the combination of (the data, and classifier) is unique per team. 
* The team members should be 4 at maximum. 
* For those who will select the third or fourth suggested dataset, the team members are allowed to be 5

## Project Deliverables

* A Github repo of the Python implementation of the system 

* Presentation includes
    * Scientific background of the used classifier
    * Explanation of the dataset 
    * The classification results
    * Demo for system deployment. 

## Grading Criteria

* 50% on building the ML system
* 20% on Deploying the system on a web application.
* 20% on the presentation 
* 10% on follow-up meeting with the TA

## Resources

* A complete demo for training, saving and deploying ML model using flask is [here](https://microsoft.github.io/ML-For-Beginners/#/3-Web-App/1-Web-App/README) and the source code is [here](https://github.com/microsoft/ML-For-Beginners/tree/main/3-Web-App/1-Web-App/solution)
* Another awesome framework for deployment [fastapi](https://fastapi.tiangolo.com/)

* Another advanced framework for deployment of machine learning models [streamlit](https://streamlit.io/)

* Online Machine learning and Data science community [kaggle](https://www.kaggle.com/)

* [Scikit-Learn](https://scikit-learn.org/stable/index.html)

* [Pandas](https://scikit-learn.org/stable/index.html)

* [matplotlib](https://matplotlib.org/)
