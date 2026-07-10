# 😊 Amazon Alexa Reviews Sentiment Analysis using Natural Language Processing

This project demonstrates how to build a **Sentiment Analysis** model using **Natural Language Processing (NLP)** and **Machine Learning**. The notebook analyzes customer reviews of Amazon Alexa products, transforms text into numerical features using **CountVectorizer**, and trains a **Multinomial Naive Bayes** classifier to predict whether a review expresses **positive** or **negative** sentiment.

The project provides a practical introduction to text preprocessing, feature extraction, visualization, and sentiment classification.

---

## 📌 Features

- Exploratory Data Analysis (EDA)
- Customer review visualization
- Word Cloud generation
- Text preprocessing and cleaning
- Stopword removal
- Punctuation removal
- Feature extraction using CountVectorizer
- Train/Test split
- Multinomial Naive Bayes classifier
- Model evaluation using classification metrics

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- NLTK
- WordCloud
- Jupyter Notebook

---

## 📚 Libraries

```python
pandas
numpy
matplotlib
seaborn
scikit-learn
nltk
wordcloud
jupyterthemes
```
---

## 📊 Dataset

The project uses the **Amazon Alexa Reviews Dataset**, which contains customer feedback collected from Amazon.

### Features

- Verified Review (Review Text)
- Rating
- Feedback (Target Variable)

### Target Variable

- **Positive Review**
- **Negative Review**

The objective is to classify customer reviews according to their sentiment.

---

## 🔍 Exploratory Data Analysis

The notebook includes several exploratory analysis techniques, including:

- Dataset inspection
- Review distribution
- Rating distribution
- Word frequency analysis
- Word Cloud visualization
- Basic statistical summaries

These visualizations help understand the characteristics of customer feedback before training the model.

---

## 📝 Natural Language Processing Pipeline

Before training the classifier, the notebook preprocesses the review text by:

- Converting text into tokens
- Removing punctuation
- Removing English stopwords using **NLTK**
- Cleaning the review text
- Transforming text into numerical features using **CountVectorizer**

This preprocessing pipeline converts raw customer reviews into a format suitable for machine learning.

---

## ⚙️ Machine Learning Workflow

The notebook follows these steps:

1. Load the Amazon Alexa reviews dataset
2. Explore and visualize the data
3. Clean and preprocess review text
4. Generate a document-term matrix using **CountVectorizer**
5. Split the dataset into training and testing sets
6. Train a **Multinomial Naive Bayes** classifier
7. Generate predictions
8. Evaluate model performance

---

## 🤖 Machine Learning Model

The project uses a **Multinomial Naive Bayes** classifier, a popular algorithm for text classification tasks due to its simplicity, speed, and strong performance on bag-of-words representations.

---

## 📈 Model Evaluation

The trained model is evaluated using:

- Accuracy Score
- Confusion Matrix
- Classification Report

These metrics provide insight into how effectively the model classifies customer sentiment.

---

## 🚀 Getting Started

### Install dependencies

Install them manually:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn nltk wordcloud jupyterthemes
```

---

### Download NLTK Resources

Before running the notebook, download the required stopwords dataset:

```python
import nltk

nltk.download("stopwords")
```

---

## ▶️ Running the Project

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
Sentiment_Analysis - Skeleton.ipynb
```

Run the notebook cells sequentially to reproduce the complete sentiment analysis workflow.

---

## 🎯 Learning Objectives

This project demonstrates how to:

- Perform exploratory data analysis on text datasets
- Clean and preprocess textual data
- Remove punctuation and stopwords using NLTK
- Convert text into numerical features using CountVectorizer
- Train a Multinomial Naive Bayes classifier
- Evaluate text classification models
- Apply Natural Language Processing techniques to sentiment analysis

---

## 🔮 Future Improvements

- Compare CountVectorizer with TF-IDF Vectorization
- Experiment with Logistic Regression, Support Vector Machines, and XGBoost
- Apply stemming and lemmatization
- Fine-tune transformer models such as BERT
- Build a Streamlit web application for real-time sentiment prediction
