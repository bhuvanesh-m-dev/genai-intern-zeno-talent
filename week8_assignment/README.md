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
