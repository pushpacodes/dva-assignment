# 🌐 Multilingual Social Network Data Analysis using NLP & Machine Learning

---

## 📊 Project Overview

This project implements a **complete data analysis pipeline** for a synthetic Instagram-like social network dataset. It combines **Natural Language Processing (NLP), Machine Learning, Deep Learning, and Network Analysis** to process and analyze multilingual user-generated content.

Additionally, the system integrates **cross-lingual translation and sentiment analysis**, enabling deeper understanding of user emotions across multiple languages.

The dataset consists of **large-scale simulated records** including multilingual captions, user interactions, and network relationships.

---

## 🎯 Objectives

* Analyze multilingual text data
* Perform feature extraction and vectorization
* Apply dimensionality reduction techniques
* Build classification models for language detection
* Perform sentiment analysis on user captions
* Visualize social network relationships
* Extract insights from large-scale data

---

## ⚙️ Key Steps

* **Data Generation** – Created large-scale multilingual dataset
* **Preprocessing** – Cleaned captions (removed noise like hashtags, mentions)
* **EDA** – Language distribution & caption statistics
* **Vectorization** – TF-IDF, Bag of Words, Embeddings
* **Dimensionality Reduction** – PCA, t-SNE
* **Classification** – Logistic Regression, Naive Bayes, Random Forest, ANN
* **Translation** – Multilingual translation using transformer models
* **Sentiment Analysis** – Emotion detection (Positive / Negative / Neutral)
* **Graph Visualization** – Social network analysis using NetworkX

---

## 🧱 Dataset Description

Each record includes:

### 👤 User Profile

* User ID
* Username
* Location
* Followers & Following count

### 📝 Content Data

* Post ID
* Caption (Multilingual)
* Language label

### 🔗 Interaction Data

* Hashtags
* Mentions

### 🌐 Network Data

* Friend connections
* Suggested users

### 📊 Engagement Metrics

* Likes
* Comments
* Shares

---

## ⚙️ Methodology

### 🔹 Step 1: Data Generation

* Generated synthetic multilingual dataset

### 🔹 Step 2: Data Loading & Exploration

* Loaded dataset
* Verified structure and samples

### 🔹 Step 3: Exploratory Data Analysis (EDA)

* Language distribution
* Caption length statistics
* Engagement analysis

### 🔹 Step 4: Visualization (Before Preprocessing)

* Language count plots
* Caption length distribution

### 🔹 Step 5: Text Preprocessing

* Removed URLs, hashtags, mentions
* Cleaned and normalized text

### 🔹 Step 6: Visualization (After Preprocessing)

* Compared before vs after cleaning

### 🔹 Step 7: Feature Extraction

#### ✔ TF-IDF

* Importance-based word representation

#### ✔ Bag of Words

* Frequency-based representation

#### ✔ Transformer Embeddings (IndicBERT)

* Used IndicBERT model
* Captured contextual semantic representations

### 🔹 Step 8: Dimensionality Reduction

#### ✔ PCA

* Reduced feature dimensions

#### ✔ t-SNE

* Visualized clustering

### 🔹 Step 9: Classification Models

#### ✔ Machine Learning

* Logistic Regression
* Naive Bayes
* Random Forest

#### ✔ Deep Learning

* Artificial Neural Network (ANN)

* Predicted language labels

### 🔹 Step 10: Translation

* Multilingual translation using transformer models (many-to-many)

### 🔹 Step 11: Visualization

* Plotted distributions and analysis graphs

### 🔹 Step 11.5: Sentiment Analysis

* Applied transformer-based sentiment pipeline
* Evaluated using accuracy, precision, recall, F1-score

### 🔹 Step 12: Network Graph Visualization

* Built graph using NetworkX
* Identified influential users using centrality
* Built graph using NetworkX
* Identified influential users using centrality

---

## 📈 Results

* High accuracy in language classification
* Clear clustering in embeddings
* Improved performance after preprocessing
* Accurate multilingual translation
* Effective sentiment detection
* Network graphs revealed influential users

---

## 💡 Key Insights

* Multilingual translation enables unified analysis
* Sentiment analysis reveals user behavior patterns
* Combining ML + DL improves accuracy
* Network analysis highlights key influencers

---

## 🛠️ Technologies Used

* Python
* NumPy, Pandas
* Scikit-learn
* TensorFlow / Keras
* Transformers (NLLB, BERT, MiniLM)
* Matplotlib, Seaborn
* NetworkX
* FastText

---

## 🚀 Conclusion

This project demonstrates a **comprehensive multilingual data analysis pipeline** integrating NLP, machine learning, translation, and sentiment analysis. It effectively transforms raw social media data into **meaningful insights about language, behavior, and network structure**.

---

## 🎓 Mentor

P. Srikanth

🔗 GitHub: [https://github.com/srikanth5](https://github.com/srikanth5)

---

## 👩‍💻 Authors

* K Pushpalatha - [https://github.com/pushpacodes](https://github.com/pushpacodes)
* Keerthi K - [https://github.com/K18thi](https://github.com/K18thi)

---

⭐ If you found this useful, consider giving it a star!
