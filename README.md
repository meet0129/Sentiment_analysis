# 💬 **Amazon Food Reviews – Sentiment Analysis (VADER + RoBERTa)**
A powerful sentiment analysis project that compares traditional rule-based NLP with deep learning transformers using real-world food reviews from Amazon. Built in Python, this project uses NLTK’s VADER and Hugging Face’s RoBERTa model to classify sentiment and uncover mismatches between star ratings and review tone. It achieves 87% accuracy on unseen data, making it a reliable tool for analyzing customer feedback. Ideal for understanding customer emotions through text data.🍕📈

  🚀 **Technologies Used**
  
🐍 Python 3.x – Core programming language
📚 pandas & NumPy – Data manipulation and numerical ops
📊 Matplotlib & Seaborn – Visualization tools
🧠 NLTK (VADER) – Rule-based sentiment analysis
🤗 Transformers (Hugging Face) – RoBERTa model for deep learning sentiment detection
🔡 scipy.special.softmax – Probability distribution from logits
⏱️ tqdm – Real-time progress bars during analysis
🧠 RoBERTa (cardiffnlp/twitter-roberta-base-sentiment) – Transformer model for social media style text

📌 **Project Highlights**

🧾 Uses real Amazon food product reviews (from Kaggle) with user ratings (1–5 stars)
📉 Performs exploratory data analysis (EDA) on rating distributions
🧹 Applies text preprocessing: tokenization, POS tagging
📈 Implements VADER sentiment scoring: negative, neutral, positive, and compound scores
🤖 Integrates RoBERTa-based deep learning sentiment scoring using Hugging Face
🔄 Compares VADER vs RoBERTa sentiment outputs visually and numerically
🚨 Detects and highlights rating vs sentiment mismatches (e.g. 1-star reviews with positive sentiment)
📊 Plots score trends, distribution charts, and scatter comparisons
📂 Clean and modular code using pandas DataFrames and reusable functions
✅ Achieves 87% accuracy on unseen data, showing strong generalization to real-world reviews


