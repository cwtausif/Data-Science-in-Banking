# Sentiment Analysis

This project performs sentiment analysis on customer reviews to classify them as positive, negative, or neutral. The notebook includes steps for data loading, cleaning, visualization, and sentiment analysis using various libraries and tools.

## Table of Contents
1. [Installation](#installation)
2. [Usage](#usage)
3. [Project Structure](#project-structure)
4. [Libraries Used](#libraries-used)
5. [Data Loading](#data-loading)
6. [Data Cleaning](#data-cleaning)
7. [Sentiment Analysis](#sentiment-analysis)
8. [Visualization](#visualization)
9. [Contributing](#contributing)
10. [License](#license)

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/cwtausif/Data-Science-in-Banking.git
    ```
2. Navigate to the project directory:
    ```bash
    cd sentiment-analysis
    ```
3. Install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
1. Ensure you have the dataset file (`customers.csv`) in the project directory.
2. Open the Jupyter notebook:
    ```bash
    jupyter notebook Sentiment_AnaLysis-2.ipynb
    ```
3. Run the notebook cells sequentially to perform sentiment analysis.

## Project Structure
```plaintext
sentiment-analysis/
├── Sentiment_AnaLysis-2.ipynb
├── customers.csv
├── requirements.txt
└── README.md
```


## Libraries Used
pandas
matplotlib
seaborn
numpy
wordcloud
re
textblob
spacy
sklearn
torch
transformers


## Data Loading
The dataset is loaded from a CSV file named customers.csv. The structure of the dataset is as follows:
Date        Name            ID          Type        Review                                  Rating


## Data Cleaning
Data cleaning involves:

Handling missing values
Removing duplicates
Normalizing text (lowercasing, removing punctuation, etc.)
## Sentiment Analysis
Sentiment analysis is performed using various methods including:

TextBlob for polarity scoring
Pre-trained models from the transformers library for advanced sentiment analysis
## Visualization
Visualizations include:

Word clouds
Bar charts for sentiment distribution
Heatmaps for correlation analysis

