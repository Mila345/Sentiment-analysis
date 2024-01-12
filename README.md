# Sentiment Analysis with BERT

This repository contains code and data for performing sentiment analysis using the BERT model. The project includes data cleaning and preparation, model training, testing (by plotting a confusion matrix for the two sentiment categories), and word cloud generation.

## Introduction

Sentiment analysis is the process of determining the sentiment or emotion expressed in text data. In this project, we use the German BERT model for sentiment analysis of app user reviews in German. This repository provides code and data to perform sentiment analysis on text data, including data cleaning, model training, testing, and word cloud generation.

## Table of Contents

- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Data Cleaning and Preparation](#data-cleaning-and-preparation)
- [Model Training and Testing](#model-training-and-testing)
- [Word Cloud Generation](#word-cloud-generation)
- [File Structure](#file-structure)
- [Contributing](#contributing)

## Getting Started

### Prerequisites

- Python (3.x recommended)
- Jupyter Notebook (optional)
- Required Python libraries (install using `pip`):
  - `transformers`
  - `pandas`
  - `numpy`
  - `datasets`
  - `germansentiment`
  - `nltk`
  - `seaborn`
  - `matplotlib`
  - `scikit-learn`

### Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/yourusername/sentiment-analysis-bert.git

### Data Cleaning and preparation
python training_sent_an.py

### Model training and testing
python training_sent_an.py

### Word cloud generation
python word_cloud.py

### File structure

External_data.csv: Input data set
train.csv: Training data set
test.csv: Testing data set
training_sent_an.py: Python script for data cleaning, model training, and testing
word_cloud.py: Python script for generating word clouds
requirements.txt: List of required Python libraries
results/: Directory for storing trained models and evaluation results

### Contributing
Contributions are welcome! If you have any improvements or suggestions for this project, please create a pull request or open an issue.

