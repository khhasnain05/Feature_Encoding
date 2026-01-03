# Feature Encoding

## 📌 Project Overview

This repository contains a Jupyter Notebook developed in Google Colab that demonstrates **feature encoding techniques** applied to the Student Placement Dataset obtained from Kaggle.

## 📊 Dataset Description

The Student Placement Dataset consists of **15 columns** representing academic and placement related attributes of students.

The following columns were selected for encoding because these were categorical:

* Gender  
* Branch  
* Degree  
* Placement_Status  

## 🔄 Encoding Techniques Applied

### ✅ One Hot Encoding

Applied on the following nominal features:

* Gender  
* Branch  

**Reason**  
These features do not have any inherent order.

### 🔢 Ordinal Encoding

Applied on the Degree column using this order:

1. BCA  
2. B.Sc  
3. B.Tech  
4. MCA  

**Reason**  
Academic degrees follow a natural progression.

### 🏷️ Label Encoding

Applied on Placement_Status.

**Reason**  
This column represents the output variable and must be converted into numeric form for machine learning models.

## 🛠️ Implementation Methods

### Method 1 Manual Encoding Approach

In this method:

* Each encoding technique is applied step by step  
* Clear separation of preprocessing logic  
* Beginner friendly and easy to understand  

### Method 2 ColumnTransformer Based Approach

In this method:

* ColumnTransformer is used to apply all encodings together  
* Code is clean and scalable  
* Suitable for real world machine learning pipelines  

## 👤 Author
Khawaja Hasnain
