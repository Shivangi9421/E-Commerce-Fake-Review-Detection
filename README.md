# E-Commerce-Fake-Review-Detection
Fake reviews are a major challenge in modern e-commerce platforms like Amazon, Flipkart, and Walmart. They mislead customers, manipulate ratings, and affect product credibility.
This project builds an AI-powered Fake Review Detection System using NLP, Machine Learning, and sentiment analysis to classify customer reviews as Fake or Genuine.The system analyzes review text, reviewer behavior, rating patterns, and sentiment signals to identify suspicious or bot-generated reviews. It also provides trust scores, sentiment insights, and analytical visualizations.

🚀 Key Features

1.NLP-based Fake Review Classification using TF-IDF, XGBoost, Logistic Regression, and SVM

2.Sentiment Analysis to detect emotional tone of reviews (Positive/Negative/Neutral)

3.Review Trust Score indicating probability of fake behavior

4.Advanced Feature Engineering (review length, sentiment polarity, extreme ratings, repeated text, etc.)

5.EDA & Visualization Dashboards for fake vs genuine review distribution

6.Clean ML pipeline including preprocessing, model training, evaluation, and prediction

7.Deployment-ready design with Streamlit/Flask option

🧠 Tech Stack

1.Python, Pandas, NumPy

2.NLP: NLTK, spaCy, TF-IDF, Word Embeddings

3.Machine Learning: Logistic Regression, XGBoost, SVM, Random Forest

4.Visualization: Matplotlib, Seaborn, Plotly

5.Model Deployment (optional): Streamlit / Flask

🔍 Approach & Workflow
1. Data Cleaning

Remove duplicates, URLs, HTML, emojis

Filter out very short/empty reviews

Normalize text (lowercase, tokenizing, lemmatization)

2. EDA (Exploratory Data Analysis)

Review length patterns

Frequent suspicious words

Reviewer activity anomalies

Distribution of fake vs genuine labels

3. Feature Engineering

TF-IDF vectorization

Review length (word count, char count)

Sentiment polarity score

Extreme rating flags

Duplicate review detection

4. Model Training

Models trained & compared:

Logistic Regression

SVM (LinearSVC)

Random Forest

XGBoost

Metrics used:

Accuracy

Precision

Recall

F1-Score

ROC-AUC

5. Prediction & Trust Scoring

For each review:

Fake / Genuine classification

Fake probability

Trust score (0–100)

Sentiment label

📊 Visualizations

Dashboards include:

1.Fake vs Genuine distribution

2.Sentiment polarity charts

3.Wordclouds for genuine vs fake reviews

4.Rating vs authenticity patterns

5.Suspicious reviewer behavior charts

<img width="940" height="453" alt="image" src="https://github.com/user-attachments/assets/0669aec1-7fc9-436a-a35c-ecd7486905fc" />
<img width="940" height="449" alt="image" src="https://github.com/user-attachments/assets/ca99e853-92d6-4b68-bbcb-e1f3b8653c93" />
<img width="940" height="445" alt="image" src="https://github.com/user-attachments/assets/7c967199-bcef-4923-ab1a-dc01f0cc89a4" />




Model Persistence: Joblib, Pickle
