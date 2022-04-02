# CA06_kNN_based_Recommender_Engine

## Background
At scale, this would look like recommending products on Amazon, articles on Medium, movies on
Netflix, or videos on YouTube. Although, we can be certain they all use more efficient means of making
recommendations due to the enormous volume of data they process. However, we could replicate one of
these recommender systems on a smaller scale using what we have learned here in this article. Let us
build the core of a movies recommender system.

**What question are we trying to answer?**
Given a movies data set, what are the 5 most similar movies to a movie query?

## Dataset 
The dataset can be downloaded via this link: https://github.com/krissyw/CA06_kNN_based_Recommender_Engine/blob/main/movies_recommendation_data.csv

## Code 
Python notebook can be found using this link: https://github.com/krissyw/CA06_kNN_based_Recommender_Engine/blob/main/Krissy_Wong_CA06_kNN_based_Recommender_Engine.ipynb


## Installation 
Be aready to mount the drive from Google Drive:

from google.colab import drive drive.mount('/gdrive')

In order for the program to run properly, make sure your csv files are located in paths as follows: For example: '/gdrive/MyDrive/BSAN6070/CA03/census_data.csv'


## Table of Contents 

### **1. The Application**

•  Import Packages

### **2. Data Source and Contents**

•  Mount Google Drive

•  Read the Dataset

•  Data Inspection and Quality Analysis

•  Data Cleaning and Processing

### **3. Building your own Recommender System**

•  Define a Euclidean Distance 

•  Calculate Euclidean Distance to find top 5 movies most similar to "The Post" 
