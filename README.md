# Mental Health Disorder Detection Using Deep Learning

## Overview

This project focuses on detecting different mental health disorders from textual data using a deep learning model. Social media platforms often contain posts that reflect a user's mental state. By applying Natural Language Processing (NLP), this project classifies text into different mental health categories.

## Disorders Detected

* Anxiety
* Depression
* Bipolar Disorder
* Personality Disorder
* Stress

## Dataset

The dataset contains Reddit posts related to mental health discussions.
Each text sample is labeled with a specific mental health condition.

## Model Used

The model is built using **DistilBERT**, a transformer-based language model that performs well for text classification tasks.

## Technologies Used

* Python
* PyTorch
* Transformers (Hugging Face)
* Scikit-learn
* Pandas
* NumPy

## Workflow

1. Load and preprocess the dataset
2. Tokenize text using DistilBERT tokenizer
3. Train the deep learning model
4. Evaluate the model using accuracy and classification metrics

## Evaluation Metrics

* Accuracy
* Classification Report
* Confusion Matrix

## How to Run

1. Install required libraries
2. Open the notebook in Google Colab or Jupyter Notebook
3. Run all cells to train and evaluate the model

## Future Improvements

* Use larger datasets for better performance
* Experiment with other transformer models
* Deploy the model as a web application

## Author

Shanmukhi Gudapati
