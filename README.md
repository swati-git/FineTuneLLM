# Supervised Fine-Tuning with Financial Sentiment Analysis

This project demonstrates how to perform supervised fine-tuning on language models using financial sentiment data on CPU.

## Overview

The notebook `Supervised_Fine_Tuning_With_FinancialSentiment_on_CPU.ipynb` implements a fine-tuning pipeline for sentiment analysis in financial texts. It's designed to run on CPU environments, making it accessible without requiring specialized hardware.

## Prerequisites

- Python 3.8+
- PyTorch
- Transformers
- pandas
- numpy


```bash
pip install torch transformers pandas numpy scikit-learn
```

## Dataset

The project uses a financial sentiment dataset containing:
- Financial text/news
- Sentiment labels (positive, negative, neutral)

## Features

- Data preprocessing for financial texts
- Model fine-tuning configuration for CPU
- Sentiment classification training

## Usage

1. Open the notebook in Jupyter or Google Colab
2. Install required dependencies
3. Load and preprocess the financial sentiment dataset
4. Configure and run the fine-tuning process

## Model Architecture

The notebook uses a pre-trained transformer model fine-tuned for sentiment classification tasks.
