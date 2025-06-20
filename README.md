# 📧 Spam Detection using FP-Growth and Association Rules

This project applies the **FP-Growth Pattern Mining** and **Association Rule Learning** to detect spam emails from SMS messages.

## 📌 Table of Contents

- [Dataset](#dataset)
- [Methodology](#methodology)
- [Installation](#installation)
- [How to Run](#how-to-run)
- [License](#license)
- [Credits](#credits)

---

## 📦 Dataset

Sử dụng dataset từ [SMS Spam Collection Dataset](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset).

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

## 🚀 How to Run

Clone this repo:
```bash
git clone https://github.com/KonnMjn/CS313-Spam-Detection.git
cd CS313-Spam-Detection
```
---

## 📄 License
📌 Code components are licensed under the MIT License, allowing reuse, modification, and distribution with attribution and no warranty.

📎 Non-code contents are shared under the Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0), allowing reuse with attribution for non-commercial purposes.

---

## 👨‍🏫 Credits

Lương Anh Huy – 22520550

Phạm Đông Hưng – 22520521

Phan Công Minh - 22520884

Instructor: TS. Võ Nguyễn Lê Duy

---
