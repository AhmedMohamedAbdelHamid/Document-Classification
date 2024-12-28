# Document Classification
## Overview
This repository contains a pipeline for performing text classification using a Transformer-based model powered by Hugging Face's transformers library and PyTorch. The pipeline includes data preprocessing, dataset preparation, model training, evaluation, and visualization tools.

## Models Overview

### FCNN Model
Feedforward Convolutional Neural Network (FCNN) with a series of fully connected (dense) layers. This model focuses on leveraging the power of fully connected layers to learn complex representations from the input data without utilizing convolutional or pooling operations.

### DistilBERT Model
DistilBERT is a smaller, more efficient version of the BERT (Bidirectional Encoder Representations from Transformers) model. It uses a transformer architecture, with multiple transformer blocks that include self-attention mechanisms. DistilBERT reduces the size of the original BERT model by half while retaining 97% of its language understanding capabilities. It is optimized for speed and memory efficiency.

### RoBERTa Model
RoBERTa (Robustly Optimized BERT Pretraining Approach) is a variant of BERT designed for improved performance by using dynamic masking and training on larger datasets for more iterations. The architecture is based on the transformer model, specifically designed to improve BERT by using larger mini-batches, more training data, and removing the Next Sentence Prediction task. RoBERTa generally uses more training steps and a larger corpus of data, resulting in a stronger performance on various NLP tasks.

## Training Performance (Epochs 1-100)

- FCNN Test Accuracy: 56.63%
- Val_accuracy: 54.78%
- Val_loss: 1.5149

- DistilBERT Val Accuracy: 97.75%
- DistilBERT Train Loss: 0.0434
- DistilBERT Val Loss: 0.0842

- RoBERTa Val Accuracy: 98.20%
- RoBERTa Train Loss: 0.0435
- RoBERTa Val Loss: 0.0804

## Result

- Best DistilBERT Accuracy: 98.43%
- Best RoBERTa Accuracy: 98.20%
- Best FCNN Accuracy: 51.69%

# Reference
Source: [Kaggle](https://www.kaggle.com/datasets/alfathterry/bbc-full-text-document-classification)

## License
None
