🤖 AI Echo: Your Smartest Conversational Partner

A Natural Language Processing (NLP) Sentiment Analysis Project

AI Echo is a machine learning–powered sentiment analysis tool that classifies user reviews into Positive, Neutral, or Negative categories. It provides both an interactive Streamlit app and Jupyter Notebooks for end-to-end exploration, model training, and insights.

🚀 Features

Text Preprocessing

Tokenization, stopword removal, lemmatization

Conversion to numerical features using TF-IDF

Machine Learning Models

Logistic Regression, Naïve Bayes, and Random Forest

Best model saved and deployed

Interactive Web App (app.py)

Enter custom text and get instant sentiment predictions

Visual insights into reviews (word clouds, charts, sentiment over time, etc.)

Data Exploration & Model Training

EDA.ipynb – Exploratory Data Analysis

Preprocess.ipynb – Text preprocessing pipeline

nlp.ipynb – Model training and evaluation

Insights Dashboard

Sentiment distribution and trends

Sentiment by rating, location, platform, and more

Word clouds and keyword analysis of reviews

🛠️ Project Structure
├── app.py                  # Streamlit app for predictions & insights
├── cleaned_reviews.csv      # Preprocessed dataset
├── model/
│   ├── tfidf_vectorizer.pkl # Saved TF-IDF vectorizer
│   ├── best_model.pkl       # Trained ML model
├── EDA.ipynb                # Exploratory Data Analysis
├── Preprocess.ipynb         # Data preprocessing steps
├── nlp.ipynb                # Model training and evaluation
├── requirements.txt         # Project dependencies
├── README.md                # Project documentation


📊 Example Usage

Enter Text:

"The new update is fantastic! I love using this app."

Output Prediction:

Predicted Sentiment: Positive ✅

Insights Dashboard:

View sentiment proportions

Explore word clouds for each sentiment

Track sentiment trends over time

📈 Future Enhancements

Add deep learning models (LSTM, BERT)

Deploy on cloud (Heroku / AWS / Hugging Face Spaces)

Multi-language support

Enhanced dashboard filters and drilldowns
