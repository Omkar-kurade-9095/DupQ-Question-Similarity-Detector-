# DupQ-Question-Similarity-Detector-

A machine learning and NLP-based application that detects whether two given questions are semantically similar.
This project uses advanced text preprocessing, vectorization, and classification models to identify duplicate questions with high accuracy.

# Features---

Interactive Web App built with Streamlit for easy usage.

Preprocessing pipeline for text cleaning (stopword removal, lemmatization, etc.).

TF-IDF & Word Embeddings for question representation.

Trained ML Model (e.g., Logistic Regression, XGBoost, or others) to classify question pairs.

Real-time Prediction — instantly see if questions are duplicates.

# Tech Stack----

Languages & Libraries:

Python

NumPy, pandas

Scikit-learn

NLTK / spaCy

Joblib (model saving/loading)

Streamlit (UI)

# ML Techniques:

Text preprocessing & normalization

TF-IDF vectorization

# Installation & Setup

Clone the repository
git clone https://github.com/your-username/DupQ-Question-Similarity-Detector.git
cd DupQ-Question-Similarity-Detector

Create and activate virtual environment

python -m venv myenv
myenv\Scripts\activate   # Windows
source myenv/bin/activate

# Install dependencies

pip install -r requirements.txt


# Run the application

streamlit run app.py

Usage

Open the app in your browser (Streamlit will provide a local URL).

Enter two questions in the input boxes.

Click Predict.

The app will output "Duplicate" or "Not Duplicate" along with the similarity score.

# Dataset

This project uses the Quora Question Pairs Dataset containing pairs of questions and a label indicating whether they are duplicates.

# Results

Accuracy: XX%

F1-score: XX%

Model trained on ~400K question pairs with optimized hyperparameters.

# Future Improvements

Integrate BERT/RoBERTa embeddings for better semantic understanding.

Add API endpoints for programmatic access.

Deploy on Streamlit Cloud / Hugging Face Spaces.

Cosine similarity / distance-based features

Classification model training
