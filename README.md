# NER for mountains

## Project Overview

This repository focuses on using Named Entity Recognition (NER) techniques with neural networks to identify mountain names within text. By training models on annotated datasets, the goal is to accurately detect and extract mountain names from unstructured data.

## Data Preparation

1. **Data Source**: Text data was gathered through web scraping from various mountain-related websites.
2. **Preprocessing**: The raw text was cleaned and manually annotated to highlight mountain names, forming the dataset used for training.

## Model Development

1. **Model Architecture**: The BERT (Bidirectional Encoder Representations from Transformers) architecture was utilized for token classification to identify mountain names.
2. **Tokenization**: The dataset was tokenized, with labels aligned to each token for effective training.
3. **Fine-Tuning**: BERT was fine-tuned on the annotated dataset to improve recognition accuracy.

## Model Evaluation & Inference

1. **Evaluation**: After training, the model was tested on unseen text to evaluate its performance in identifying mountain names.
2. **Inference**: The trained model can be used to predict mountain names in any input text.

## Future Enhancements

1. **Dataset Expansion**: Collect additional data from more diverse mountain-related sources to further refine the model.
2. **Model Optimization**: Test different NER models and fine-tune hyperparameters to improve performance.
3. **Name Variations**: Implement techniques to handle different name formats, including abbreviations and alternative spellings.

## How to Use

To run the model for training or inference, use the following scripts:

```bash
python model_training.py
python model_inference.py
```
