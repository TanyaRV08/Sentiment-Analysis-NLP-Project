# Sentiment Analysis on Text Data (NLP)

This project demonstrates how to build a **Natural Language Processing (NLP)** model to analyze text sentiment using **TF-IDF vectorization** and **Logistic Regression**.  
The model classifies text samples as **Positive**, **Negative**, or **Neutral**.

---

## Project Overview

The goal of this project is to predict the **sentiment polarity** of given text data — for example, determining whether a review or message expresses a positive, negative, or neutral opinion.

This type of analysis is widely used in:
- Product and movie review analysis  
- Customer feedback monitoring  
- Social media sentiment tracking  
- Brand reputation management  

---

## Dataset

- **File:** `sentiment_data.csv`  
- **Columns:**
  - `Text` — textual content (reviews, comments, etc.)  
  - `Sentiment` — target label (`Positive`, `Negative`, or `Neutral`)

You can replace this dataset with any CSV containing these two columns.

---

## Model Workflow

1. **Import Libraries** — pandas, scikit-learn  
2. **Load Dataset** — read `sentiment_data.csv`  
3. **Data Exploration** — check sentiment distribution and data structure  
4. **Text Vectorization** — convert text into numeric features using **TF-IDF**  
5. **Train-Test Split** — 80% training, 20% testing (stratified)  
6. **Model Training** — Logistic Regression with max_iter=1000  
7. **Model Evaluation** — Accuracy, Confusion Matrix, Classification Report  
8. **Prediction on New Text** — test the model on unseen sentences

