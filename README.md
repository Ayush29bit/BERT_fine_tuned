# BERT_fine_tuned
Fine tuning BERT transformers model using Hugging Face Transformers library 

 BERT Fine-Tuned on Rotten Tomatoes Sentiment Dataset
 Overview

This project fine-tunes a BERT-based model for sentiment classification using the Rotten Tomatoes movie reviews dataset. The task is a 3-class classification problem — categorizing reviews as positive, negative, or neutral.

The notebook walks through every stage of the NLP pipeline: dataset loading, preprocessing, model fine-tuning, evaluation, and saving the final model for inference.

 Key Features

 End-to-end BERT fine-tuning pipeline using Hugging Face
 Uses Rotten Tomatoes dataset from the datasets library
 Implements custom evaluation metrics (weighted F1-score)
 Fine-tunes bert-base-uncased on labeled text data
 Saves trained model and tokenizer for later inference

 Model Details
Component :	Description
Base Model : bert-base-uncased
Task : Text Sentiment Classification
Dataset :	Rotten Tomatoes (datasets library)
Labels :	3 (Positive, Neutral, Negative)
Metric :	Weighted F1-Score
Library Stack :	Transformers, Datasets, Evaluate, Accelerate
