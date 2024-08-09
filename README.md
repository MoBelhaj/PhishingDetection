# **Phishing Email Detection Model**

This repository contains a Phishing Email Detection Model developed using deep learning techniques. The model is designed to identify phishing emails based on their textual content, utilizing Recurrent Neural Networks (RNN) and Long Short-Term Memory (LSTM) layers.

## **Table of Contents**

1. [Introduction](#introduction)
2. [Dataset](#dataset)
3. [Modeling Process](#modeling-process)
   - [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
   - [Text Preprocessing](#text-preprocessing)
   - [Model Building](#model-building)
   - [Model Evaluation](#model-evaluation)
4. [Usage](#usage)
5. [Results](#results)

## **Introduction**

This project aims to detect phishing emails by analyzing their textual content. The model leverages Natural Language Processing (NLP) techniques combined with deep learning models like Recurrent Neural Networks (RNN) and Long Short-Term Memory (LSTM) networks to achieve accurate classification.

## **Dataset**

The dataset used in this project contains email texts labeled as either "safe" or "phishing." The data undergoes extensive preprocessing to clean and prepare it for the modeling process.

## **Modeling Process**

### **Exploratory Data Analysis (EDA)**

- The dataset is initially cleaned by removing null values and duplicates.
- A categorical distribution of email types is visualized to understand the balance between "safe" and "phishing" emails.

### **Text Preprocessing**

- Text preprocessing involves:
  - Removing hyperlinks
  - Stripping out punctuations
  - Converting text to lowercase
  - Eliminating extra spaces
- The processed text is then prepared for the deep learning models through tokenization and padding.

### **Model Building**

- Two deep learning models are developed:
  - **Simple RNN Model:** A Recurrent Neural Network designed for basic sequence learning and classification.
  - **LSTM Model:** A more advanced model using Long Short-Term Memory layers to capture long-term dependencies in the text, improving classification performance.

### **Model Evaluation**

- The models are evaluated on their accuracy, loss, and confusion matrix.
- Training history is visualized to provide insights into the model's learning process.

## **Usage**

Once trained, the model can be used to classify new email texts as either phishing or safe. The model's output includes a trust score, indicating the confidence level of the prediction.

## **Results**

The Model demonstrates strong performance, achieving high accuracy in detecting phishing emails.
![image](https://github.com/user-attachments/assets/58ad0c02-d0d8-4a8d-8eeb-faa1f86bc899)
![image](https://github.com/user-attachments/assets/1c1ebd4d-819e-48e9-8764-ab5edfcc117c)


