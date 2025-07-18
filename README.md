# COVID-19 Tweets Sentiment Analysis 🦠📊

This project performs sentiment analysis on tweets related to COVID-19 using a labeled dataset. It involves data exploration, preprocessing, model training (including CNN), and answering key questions from the data.

---

## 📁 Dataset Features

The dataset includes the following columns:

- **UserName**: Twitter user who posted the tweet.
- **ScreenName**: The user's Twitter handle (e.g., `@user123`).
- **Location**: User-provided location from their profile (can be blank/messy).
- **TweetAt**: Date the tweet was posted (`DD/MM/YYYY` format).
- **OriginalTweet**: Full text of the tweet.
- **Label**: Sentiment category:
  - Extremely Positive
  - Positive
  - Neutral
  - Negative
  - Extremely Negative

---

## 🔍 Project Sections

### 1. Exploratory Data Analysis
- Distribution of sentiments.
- Common words in each sentiment class.
- Frequent hashtags.

### 2. Data Cleaning & Preprocessing
- Text normalization (lowercasing, removing stopwords, etc.)
- Tokenization and TF-IDF vectorization.
- Sentiment encoding.

### 3. Train-Test Split
- The data is split into training and test sets for model evaluation.

### 4. Model Comparisons
- Logistic Regression
- Support Vector Machine (SVM)
- Convolutional Neural Network (CNN)

Models are evaluated using:
- Accuracy
- Confusion Matrix
- Classification Report

### 5. CNN for Sentiment Classification
- Word Embedding layer
- 1D Convolution + Max Pooling
- Dense layers with softmax activation

---

## ❓ Key Questions Answered

- What are the most common hashtags for each sentiment?
- What are the most frequent words used in negative vs. positive tweets?
- How do different models perform on the classification task?

---

## 🧰 Requirements

```bash
pandas
numpy
matplotlib
seaborn
scikit-learn
tensorflow / keras
nltk
