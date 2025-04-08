# Phishing URL Detection using Machine Learning

This project aims to detect phishing websites using a manually engineered feature set from URLs and training a machine learning model from scratch — all implemented in Python.

### Project Structure


## How to Run

### 1. Clone the Repository
bash
git clone https://github.com/radhika2022decode/Phishing-classifier.git
cd Phishing-classifier


### 2. Unzip the dataset in same directory
phishing_site_urls.csv

### 3. Load dataset
df = pd.read_csv("path_to_your_extracted_csv/phishing_site_urls.csv")

## Features
Manual feature extraction from URLs (e.g., URL length, presence of IP, suspicious keywords)

Data preprocessing (label encoding, scaling)

Model training using RandomForestClassifier

Testing the model with user-input URLs

Visualization (plots)

No pre-trained models or libraries are used for feature extraction

## Sample urls
https://example.com/login.php
http://192.168.1.1/verify-account
https://www.google.com
http://bit.ly/securebanking

## Install required packages
pip install -r requirements.txt
pip install notebook
jupyter notebook

