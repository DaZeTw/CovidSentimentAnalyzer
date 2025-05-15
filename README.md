# COVID-19 Sentiment Analyzer

## Table of Contents

- [Overview](#overview)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Conclusion](#conclusion)

## Overview

The COVID-19 Sentiment Analyzer project aims to analyze public sentiment regarding the COVID-19 pandemic using machine learning techniques. This project involves data collection, preprocessing, sentiment analysis using various models, and visualization of results. The project is implemented in Python and uses libraries such as Pandas, Scikit-learn, and Matplotlib.

### Dataset Overview

The dataset used in this project includes tweets related to COVID-19. The data is preprocessed to remove noise and irrelevant information, and then labeled for sentiment analysis. The features used in the analysis include the tweet text and various metadata.

## Installation

To run this project locally, follow these steps:

1. **Clone the repository**:

   ```bash
   git clone https://github.com/DaZeTw/covid-sentiment-analyzer.git
   cd covid-sentiment-analyzer
   ```

2. **Create a virtual environment** (optional but recommended):

   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows, use `venv\Scripts\activate`
   ```

3. **Install the required packages**:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. **Data Collection**: Collect tweets related to COVID-19 using the Twitter API and save them to a CSV file.
2. **Data Preprocessing**: Load and preprocess the dataset to clean the text and prepare it for analysis.
3. **Sentiment Analysis**: Perform sentiment analysis using machine learning models such as Logistic Regression, Naive Bayes, and Support Vector Machines.
4. **Visualization**: Visualize the results using Matplotlib.

### Running the Script

To run the main script, use:

```bash
python covidsentimentanalyzer.py
```

### Google Colab Notebook

For an interactive version of this project, you can view and run the code in Google Colab: [Google Colab Notebook](https://colab.research.google.com/drive/1tWpVgQlKs9bZ6MGfzmsqij_UTZmF0QwA?usp=sharing)

## Conclusion

The COVID-19 Sentiment Analyzer successfully demonstrates the application of machine learning techniques to understand public sentiment during the pandemic. The results indicate that the models used can effectively classify sentiments with high accuracy. Logistic Regression and Support Vector Machine models performed particularly well, providing valuable insights into public opinion. Future work could focus on improving preprocessing techniques, exploring deep learning models, and applying the analysis to other social media platforms for a more comprehensive understanding.
