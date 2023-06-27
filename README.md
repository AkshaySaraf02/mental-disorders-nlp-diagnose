
# Mental Disorders Classification using NLP 🧠

## Table of Contents
1. [Overview](#overview)
2. [Demo](#demo)
3. [Goals](#goals)
4. [Technical Aspect](#technical-aspect)
5. [Installation](#installation)
6. [To Do](#to-do)
7. [Technologies Used](#technologies-used)
8. [License](#license)

## Overview

This project focuses on classifying mental health-related text data into different categories using the Multinomial Naive Bayes algorithm. The goal is to predict the subreddit category based on the textual content of posts. The project involves data preprocessing, feature extraction, model training, and evaluation.

## Demo

To use the trained model for prediction, you can use the `diagnose()` function provided in the code. Pass a text as input to the function, and it will predict the corresponding mental health category.

Example usage:
```python
diagnose("I feel anxious all the time")
```

#### Important: 
Please refer to the working [demonstration](https://drive.google.com/drive/folders/1WVuhZLrMnsr6eudSgG000vKTjCT6n-8P?usp=sharing) of the NLP model for further understanding.

## Goals

The main goals of this project are:
- Classify mental health-related text data into different categories. ✅
- Build a machine learning model using the Multinomial Naive Bayes algorithm. ✅
- Evaluate the model's performance using classification metrics. ✅

## Technical Aspect

The project involves the following technical aspects: ⚙️
- Importing required libraries such as pandas, numpy, matplotlib, sklearn, and nltk.
- Loading and preprocessing the dataset.
- Performing tokenization, removing stopwords, and lemmatization on the text data.
- Balancing the dataset by selecting a subset of data from each category.
- Using CountVectorizer for feature extraction.
- Training a Multinomial Naive Bayes model on the preprocessed data.
- Evaluating the model's performance using classification metrics.
- Implementing hyperparameter tuning using GridSearchCV to optimize the model.

## Installation

To run the project locally, follow these steps:

1. Clone the repository:

```
git clone https://github.com/AkshaySaraf02/mental-disorders-nlp-diagnose
```

2. Install the required libraries:

```
pip install pandas numpy matplotlib scikit-learn nltk
```

3. Open the project in your preferred Python environment.

4. Run the code in the provided Python script or Jupyter Notebook.

## To Do

Some possible improvements or additions to the project could include:
- Exploratory data analysis to gain insights into the dataset.
- Trying different classification algorithms and comparing their performance.
- Building a web interface or API for easy interaction with the model.
- Deploying the model on a cloud platform for real-time predictions.

## Technologies Used

The project utilizes the following technologies and libraries:
- Python
- pandas
- numpy
- matplotlib
- scikit-learn
- nltk

## License

This project is licensed under the [MIT License](LICENSE).
