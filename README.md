# 🚫 Offensive Content Detection in Kannada

Detecting offensive and abusive content in **Kannada and Kannada-English code-mixed text** using Deep Learning (BiLSTM).

> 📄 Published at **DravidianLangTech Workshop @ ACL 2024**

---

## 📌 About the Project

With the explosion of regional-language social media content in India, offensive content moderation in languages like Kannada is a critical unsolved challenge. English-based moderation tools completely miss abuse in Dravidian languages.

This project builds a BiLSTM-based classifier for Kannada offensive content — one of the first published systems for this task.

**Real-world applications:**
- Social media content moderation (Twitter/X, YouTube, Facebook)
- Regional-language comment filtering
- Online community safety tools

---

## 🛠️ Tech Stack

| Component | Technology |
|---|---|
| Language | Python |
| Model | BiLSTM (Bidirectional LSTM) |
| Framework | TensorFlow / Keras |
| NLP | Tokenization, Word Embeddings |
| Data | Kannada & Kannada-English code-mixed text |

---

## 📊 Results

| Metric | Score |
|---|---|
| F1 Score | 0.61 |
| Task | Offensive content classification |
| Language | Kannada / Kannada-English |

> Note: F1 of 0.61 on Kannada is competitive given the extreme scarcity of labeled data for this low-resource language.

---

## ⚙️ Pipeline Overview

```
Raw Kannada Social Media Text
        ↓
Preprocessing & Tokenization
        ↓
Word Embedding Layer
        ↓
BiLSTM Layers (forward + backward context)
        ↓
Classification: Offensive ⚠️ / Not Offensive ✅
```

---

## 🚀 Getting Started

### Prerequisites
```bash
Python 3.8+
Jupyter Notebook
```

### Installation
```bash
git clone https://github.com/Subhadevik/Offensive_content_detection.git
cd Offensive_content_detection
pip install tensorflow keras pandas numpy scikit-learn jupyter
```

### Run
```bash
jupyter notebook
```
Open the notebook and run all cells sequentially.

---

## 🌐 Why This Research Matters

Kannada is spoken by **44 million+ people** but has almost no NLP tooling compared to English. This work directly contributes to the safety of regional-language internet users who are currently unprotected by existing moderation systems.

The **BiLSTM architecture** captures both past and future context in a sentence — essential for detecting implicit and contextual offensive language.

---

## 📄 Publication

**Offensive Content Detection in Kannada using Deep Learning**
*DravidianLangTech Workshop @ ACL 2024* — Co-author

---

## 👩‍💻 Author

**Subhadevi Krishnaraj**
- 🔗 [LinkedIn](https://www.linkedin.com/in/subhadevi-krishnaraj)
- 🐙 [GitHub](https://github.com/Subhadevik)
- 📧 subhadevi333@gmail.com
