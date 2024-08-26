# Human Rights and Law Model

This project involves training and fine-tuning a DistilBERT model for classifying human rights articles and legal documents. The goal is to develop a model that can return the most relevant human rights or legal information based on a given query.

## Project Overview

Datasets
1. Dataset1 & Dataset2:
- Contains human rights articles fetched from different sources.
  
2. Dataset3:
- Contains legal documents with titles and descriptions.
  
3. Dataset4:
- Contains specific human rights and their descriptions.

## Objectives
- Human Rights Dataset: Fine-tune a model to classify queries into specific human rights categories.
- Legal Dataset: Fine-tune a model to classify queries into legal titles and provide descriptions.

## Getting Started
### Requirements
- Python 3.7+
- PyTorch
- Transformers library from Hugging Face
- Pandas
- Datasets library from Hugging Face
Install the required packages using the provided commands.

## Data Preparation

1. Preprocessing:
- Convert the text data from the datasets into CSV format.
- Apply both basic and advanced preprocessing to clean and tokenize the text data.

2. Human Rights Dataset:
Merge datasets (Dataset1, Dataset2, Dataset4).
Save the preprocessed data for training.

3. Legal Dataset:
Convert titles and descriptions into a suitable format for classification.
Save the preprocessed data for training.

4. Model Training
- Load Preprocessed Data:
    Use pandas to load the preprocessed CSV files.
    Convert data into the appropriate format required for training.
- Fine-Tuning:
    Use DistilBERT for sequence classification.
    Define training parameters and initialize the training process.
5. Prediction
- Load Model and Tokenizer:
    Load the fine-tuned model and tokenizer for making predictions.
- Make Predictions:
    Input a query to get the most relevant law title or human rights category.

Notes
Ensure consistency between the labels used during training and those used for predictions.
Modify the model and tokenization process as needed for different datasets.

License
This project is licensed under the MIT License.

