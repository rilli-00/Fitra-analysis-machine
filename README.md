# Fitra Machine Learning System

## Overview

This repository contains the machine learning component of the Fitra platform, an AI-powered system designed to analyze YouTube content and identify videos that may contain LGBTQ+ topics for children.

The system performs the following tasks:

* Collecting and preparing video data.
* Processing and cleaning text transcripts.
* Training deep learning models for content classification.
* Evaluating model performance using standard metrics.
* Analyzing new content and generating predictions.

## Project Structure

* Data Collection: Scripts used to gather and prepare datasets.
* Model Training: Training pipeline for the CNN-LSTM classification model.
* Model Evaluation: Performance evaluation and metrics analysis.
* Content Analysis: Applying the trained model to new content.
* Report: Documentation of the machine learning methodology and results.

## Technologies Used

* Python
* TensorFlow / Keras
* Pandas
* NumPy
* Scikit-learn
* Whisper Speech Recognition

## Model Objective

The model is designed to classify content into:

* Safe
* unsafe

to support content moderation and parental control features within the Fitra platform.

## Author

Reem Abdullah Alharbi
