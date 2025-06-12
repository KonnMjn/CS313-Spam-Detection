# 📧 Spam Detection using FP-Growth and Association Rules

This project applies the **FP-Growth Pattern Mining** and **Association Rule Learning** to detect spam emails from SMS messages.

> 📁 Jupyter Notebook: [`FPGrowth_Spam-Detection.ipynb`](./FPGrowth_Spam-Detection.ipynb)  
> 🎥 Presentation Slides: [`Project Presentation.pdf`](./slides/Project%20Presentation.pdf)

---

## 📌 Table of Contents

- [Dataset](#dataset)
- [Methodology](#methodology)
- [Installation](#installation)
- [How to Run](#how-to-run)
- [Results](#results)
- [Credits](#credits)

---

## 📊 Dataset

We used the SMS Spam Collection Dataset from [Kaggle](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset).

- **Total messages:** 5,572
- **Spam:** 747 (13.4%)
- **Ham:** 4,825 (86.6%)
- **Preprocessed:** cleaned, tokenized, removed stopwords, label-encoded

---

## ⚙️ Methodology

- Text preprocessing (cleaning, stopword removal, tokenization)
- Convert each message into a set of items (words)
- Apply **FP-Growth** to mine frequent word patterns
- Generate **Association Rules**
- Classify test messages based on the strongest matched rules (spam or ham)

---

## 💻 Installation

1. Clone this repo:
```bash
git clone https://github.com/yourusername/spam-detection-fpgrowth.git
cd spam-detection-fpgrowth
