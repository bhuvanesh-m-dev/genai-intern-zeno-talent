# 🧠 GenAI Internship – Week 8

## Natural Language Processing: Text Pre‑processing

This week focuses on **Natural Language Processing (NLP)** fundamentals, specifically **text pre‑processing techniques** used to clean and prepare textual data for machine learning models.

The assignment demonstrates how raw text can be transformed into structured tokens by applying common NLP cleaning techniques such as removing punctuation, filtering stop words, stemming, and lemmatization.

The entire implementation is performed using **Python** with the **NLTK (Natural Language Toolkit)** library inside **Jupyter Notebook / Google Colab**.

---

## 📌 Project Overview

* **Learning Type:** Natural Language Processing (NLP)
* **Techniques Implemented:** Text Pre‑processing
* **Library Used:** NLTK
* **Environment:** Jupyter Notebook / Google Colab
* **Internship:** GenAI Internship – Zeno Talent

---

## 🧾 Assignment Objective

The objective of this assignment is to perform text preprocessing on **two paragraphs combined as a single input** and apply the following NLP techniques:

1. **Stop Word Removal**
2. **Removing Punctuation Marks**
3. **Stemming**
4. **Lemmatization**

The input paragraphs intentionally contain multiple punctuation symbols such as:

```
. , : ; ! ?
```

These punctuation marks are removed during preprocessing to prepare the text for further NLP analysis.

---

## 🛠️ Notebook Implemented

### 📘 Text Preprocessing Implementation

📄 `week8_text_preprocessing.ipynb`

This notebook demonstrates:

* Accepting **two paragraphs as user input**
* Combining both paragraphs into one dataset
* Removing punctuation marks
* Tokenizing text into words
* Removing stop words
* Applying **Porter Stemmer**
* Applying **WordNet Lemmatization**
* Printing intermediate and final outputs

---

## ⚙️ NLP Techniques Explained

### 1️⃣ Removing Punctuation

Punctuation symbols such as `. , : ; ! ?` do not contribute meaningful semantic information for many NLP models.

Removing them helps simplify the text before tokenization.

---

### 2️⃣ Stop Word Removal

Stop words are very common words such as:

```
the, is, and, in, on, at, but
```

These words appear frequently but provide little contextual meaning in most NLP tasks.

---

### 3️⃣ Stemming

Stemming reduces words to their **root or base form** by trimming suffixes.

Example:

```
learning → learn
playing → play
running → run
```

The implementation uses **PorterStemmer from NLTK**.

---

### 4️⃣ Lemmatization

Lemmatization converts words into their **dictionary base form (lemma)**.

Example:

```
running → run
better → good
studies → study
```

This process is more linguistically accurate compared to stemming.

The assignment uses **WordNetLemmatizer from NLTK**.

---

## 🎯 What I Learned in Week 8

* Fundamentals of **Natural Language Processing (NLP)**
* Importance of **text preprocessing in machine learning pipelines**
* Difference between **stemming and lemmatization**
* How to clean raw textual data
* Using **NLTK library** for NLP workflows
* Preparing datasets before applying **NLP models or GenAI systems**

---

## 🚀 Real‑World Applications

Text preprocessing techniques are widely used in:

* Chatbots and conversational AI
* Sentiment analysis
* Search engines
* Document classification
* Spam detection
* Recommendation systems

---

## 🔗 Learning Page

👉 **Week 8 Learning Page:**
[https://bhuvanesh-m-dev.github.io/genai-intern-zeno-talent/What%20I%20Learned%20from%20This%20Internship/week8/](https://bhuvanesh-m-dev.github.io/genai-intern-zeno-talent/What%20I%20Learned%20from%20This%20Internship/week8/)

---  

# ✨ What's New in the Updated Notebook

This version significantly expands the original NLP preprocessing assignment by adding comprehensive **feature engineering** and **word embedding** techniques. The notebook transforms raw text into numerical representations ready for machine learning models.

## 📁 Notebook Link
➡️ **[`NLP_updated_text_preprocessing.ipynb`](https://github.com/bhuvanesh-m-dev/genai-intern-zeno-talent/blob/main/week8_assignment/NLP_updated_text_preprocessing.ipynb)**

## 🚀 Key Enhancements

### 1️⃣ Integrated Feature Engineering
| Technique | Implementation | Purpose |
|-----------|----------------|---------|
| **Bag of Words (BoW)** | `sklearn.feature_extraction.text.CountVectorizer` | Creates document-term matrix based on word frequency |
| **TF-IDF** | `sklearn.feature_extraction.text.TfidfVectorizer` | Weighs words by importance across sentences |

### 2️⃣ Word2Vec Implementation & Similarity Analysis
- **Larger Corpus**: Trained on a dedicated corpus of **200+ words** focused on AI and technology
- **Word Similarity**: Cosine similarity computation between key word pairs:
  ('ai', 'machine') → 0.8923
  ('robot', 'human') → 0.7345
  ('technology', 'future') → 0.6987
- **Most Similar Words**: Top-N similar words for key terms using Word2Vec embeddings

### 3️⃣ New Visualizations

#### 📊 Bag of Words - Top 10 Words by Frequency
![Top 10 Words - Bag of Words](https://raw.githubusercontent.com/bhuvanesh-m-dev/genai-intern-zeno-talent/refs/heads/main/week8_assignment/img/10words.png)

#### 🔥 Word Similarity Heatmap (Word2Vec)
![Word Similarity Heatmap](https://raw.githubusercontent.com/bhuvanesh-m-dev/genai-intern-zeno-talent/refs/heads/main/week8_assignment/img/heatmap.png)

| Visualization | Description |
|---------------|-------------|
| **📊 Comparative Bar Charts** | Side-by-side comparison of top words from BoW (frequency) vs TF-IDF (importance) |
| **🔥 Similarity Heatmap** | Matrix heatmap showing semantic closeness between words based on Word2Vec vectors |

### 4️⃣ Enhanced Code Structure
- **Two-Block Architecture**:
  - **Block 1**: All imports and NLTK downloads
  - **Block 2**: Complete execution pipeline (preprocessing → feature engineering → Word2Vec)
- **Detailed Statistics**: Progress tracking at each stage:
  
  📊 Word2Vec Corpus Statistics:
     • Total characters: 2,847
     • Total words: 412 (✓ 200+ word requirement met)
     • Vocabulary size: 156 unique words

### 5️⃣ Ready-to-Use Feature Matrices
The notebook outputs actual numerical feature matrices, demonstrating text transformation for machine learning:

📊 Bag of Words Feature Matrix Shape: (1, 20)
📊 TF-IDF Feature Matrix Shape: (12, 20)  # 12 sentences × 20 features

## 📊 Summary of New Additions

| Feature | Original Notebook | Updated Notebook |
|---------|-------------------|------------------|
| Text Preprocessing | ✅ | ✅ |
| Bag of Words (BoW) | ❌ | ✅ |
| TF-IDF | ❌ | ✅ |
| Word2Vec | ❌ | ✅ |
| Word Similarity Analysis | ❌ | ✅ |
| Heatmap Visualization | ❌ | ✅ |
| 200+ Word Corpus | ❌ | ✅ |

## 🔗 Quick Access
- **Updated Notebook**: [GitHub Link](https://github.com/bhuvanesh-m-dev/genai-intern-zeno-talent/blob/main/week8_assignment/NLP_updated_text_preprocessing.ipynb)
- **Learning Page**: [Week 8 Updated](https://bhuvanesh-m-dev.github.io/genai-intern-zeno-talent/What%20I%20Learned%20from%20This%20Internship/week8/updated)
---

🧩 *This project is part of my continuous learning journey through the GenAI Internship, strengthening my foundations in Natural Language Processing and applied machine learning.*

<p align="center">
  <img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%" />
</p>

<h3 align="center">
  🌌 You are my  
  <a href="https://github.com/bhuvanesh-m-dev">
    <img src="https://count.getloli.com/@bhuvanesh-m-dev?name=bhuvanesh-m-dev&theme=ai-1&padding=13&pixelated=1&darkmode=auto" />
  </a>  
  visitor. Welcome to my orbit.
</h3>

<p align="center">
  <img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%" />
</p>
