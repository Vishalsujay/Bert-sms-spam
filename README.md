# SMS Fraud Detection Using BERT

This project implements a fraud detection system for SMS messages using a fine-tuned BERT model. The goal is to classify incoming messages as spam (fraudulent) or ham (legitimate) with high accuracy.

## Project Structure

- `spam_detection_bert.py` – Main script for training and evaluating the model.  
- `dataset/` – Directory containing the SMS spam dataset.  
- `README.md` – Project documentation.  

## Features

- Uses a pre-trained BERT model for text classification.  
- Fine-tuned on an SMS spam detection dataset.  
- Detects and classifies spam messages with high accuracy.  
- Implements data preprocessing and tokenization.  

## Installation

Ensure Python is installed, then install dependencies using:

```bash
pip install -r requirements.txt
# Bert-sms-spam
A spam detection model using BERT to classify messages as spam or not. This project fine-tunes a pre-trained BERT model on a spam dataset to achieve high accuracy in text classification
