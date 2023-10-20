# Naive Bayes Multi-Class Text Classification

## Overview

This project emerged as a side project while I was assisting a friend in completing their undergraduate thesis using a different model. In this project, we focus on the application of the Naive Bayes model, known for its unique strengths, to a multi-class text classification problem. The primary motivation for this project was its time-efficiency, as I was concurrently working on my own thesis.

The central objective of this project is to examine how the Naive Bayes model performs when classifying text into multiple categories, involving a combination of sentence categories and sentence polarity.

## Data Source

The dataset used in this project is obtained from the SemEval-2016 Task 5 benchmark. Specifically, we used the "restaurant" domain subset of Subtask 1, which comprises various types of English language reviews sourced from web pages. You can access this dataset at [SemEval-2016 Task 5 Dataset](http://alt.qcri.org/semeval2016/task5/).

## Analysis Steps

In this analysis, we follow these seven key steps:

1. **Connecting Colaboratory to Google Drive**: Establishing the project environment.

2. **Importing Packages & Libraries**: Importing the necessary Python libraries for data analysis.

3. **Importing Data**: Loading the dataset for analysis.

4. **Initial Exploratory Data Analysis (EDA)**: Exploring the dataset to understand its structure and content.

5. **Data Cleaning**: Preparing the dataset for analysis by addressing any data quality issues.

6. **Final Cleaned Data**: The processed and cleaned dataset ready for deeper analysis.

7. **Gaining Insights**: Extracting meaningful insights and performing text classification using the Naive Bayes model.

## Categories

In this project, we classify text into categories, including but not limited to:

- RESTAURANT#PRICES
- RESTAURANT#GENERAL
- SERVICE#GENERAL
- AMBIENCE#GENERAL
- FOOD#QUALITY
- RESTAURANT#GENERAL

## Polarity

Text is classified as either:

- POSITIVE
- NEGATIVE

## Future Development

I believe this scenario offers room for further development with more comprehensive machine learning models in the future. Possible avenues include implementing neural networks like Artificial Neural Networks (ANN) using various architectures ranging from the simpler Backpropagation to more complex models such as Long Short-Term Memory (LSTM) networks, among other models.

Feel free to explore our Naive Bayes multi-class text classification project, share your thoughts, and contribute to its development!
