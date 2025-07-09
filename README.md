# 💬 Amazon Food Reviews – Sentiment Analysis (VADER + RoBERTa)

A powerful sentiment analysis project that compares traditional rule-based NLP with deep learning transformers using real-world food reviews from Amazon. Built in Python, this project uses NLTK’s VADER and Hugging Face’s RoBERTa model to classify sentiment and uncover mismatches between star ratings and review tone. Ideal for understanding customer emotions through text data. 🍕📈

## 🚀 Technologies Used

- 🐍**Python 3.x** – Programming language
- 📚**pandas & NumPy** – Data manipulation and numerical ops
- 📊**Matplotlib & Seaborn** – Visualization tools
- 🧠**NLTK (VADER)** – Rule-based sentiment analysis
- 🤗**Transformers (Hugging Face)** – PRoBERTa model for deep learning sentiment detection
- 🔡**scipy.special.softmax** – Probability distribution from logits
- ⏱️**tqdm** – Real-time progress bars during analysis
- 🧠**RoBERTa (cardiffnlp/twitter-roberta-base-sentiment)** – Transformer model for social media style text

## 📸 Project Highlights

-  Uses real Amazon food product reviews (from Kaggle) with user ratings (1–5 stars)
-  Performs exploratory data analysis (EDA) on rating distributions
-  Applies text preprocessing: tokenization, POS tagging, lemmatization
-  Implements VADER sentiment scoring: negative, neutral, positive, and compound scores
-  Integrates RoBERTa-based sentiment scoring using Hugging Face Transformers
-  Compares VADER vs RoBERTa outputs visually and numerically
-  Detects and highlights rating vs sentiment mismatches (e.g. 1-star reviews with positive sentiment)
-  Achieves 87% accuracy on unseen data, showing strong generalization to real-world reviews
-  Plots score trends, distribution charts, and scatter comparisons
-  Clean and modular code structure using pandas DataFrames and reusable functions
