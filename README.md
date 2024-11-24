# Amazon Reviews Sentiment Analysis

This project demonstrates sentiment analysis on Amazon product reviews using Python. It includes steps for data cleaning, visualization with WordClouds, text vectorization using TF-IDF, and sentiment classification with Logistic Regression. The trained model is also saved for reuse.

---

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup Instructions](#setup-instructions)
- [Usage](#usage)
- [Results](#results)
- [License](#license)

---

## Introduction
Sentiment analysis is the process of determining whether a piece of text expresses a positive or negative sentiment. In this project, we analyze customer reviews from Amazon to classify them as positive or negative.

---

## Features
- **Data Cleaning**: Preprocess raw text by removing punctuation, stop words, and converting text to lowercase.
- **Visualization**: Generate WordClouds for positive and negative reviews.
- **Text Vectorization**: Use TF-IDF to convert textual data into numerical features.
- **Classification**: Train and evaluate a Logistic Regression model.
- **Model Saving**: Save the trained model using `pickle` for future use.

---

## Technologies Used
- Python 3.x
- Libraries: 
  - `pandas`, `numpy`
  - `matplotlib`
  - `scikit-learn`
  - `nltk`
  - `wordcloud`
  - `pickle`

---

## Setup Instructions
### Prerequisites
Ensure Python 3.x and `pip` are installed on your system.

### Steps
1. Clone the repository:
   ```bash
   https://github.com/MohamadPirniakan/Amazon-Reviews-Sentiment-Analysis.git
   cd Amazon-Reviews-Sentiment-Analysis
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Download the dataset:
   - Place the dataset file `Amazon-Product-Reviews-Sentiment-Analysis-in-Python-Dataset.csv` in the project directory.

4. Run the script:
   ```bash
   python sentiment_analysis.ipynb
   ```

---

## Usage
1. Clean and preprocess the data.
2. Visualize key insights using WordClouds.
3. Train the Logistic Regression model on preprocessed text.
4. Evaluate the model using accuracy and confusion matrix.

---

## Results
The project achieves approximately **XX% accuracy** on the test set. Below are some key visualizations:

### Positive WordCloud
![Positive WordCloud](images/positive_wordcloud.png)

### Negative WordCloud
![Negative WordCloud](images/negative_wordcloud.png)

### Confusion Matrix
![Confusion Matrix](images/confusion_matrix.png)

---

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
