# 🌍 Spanish-English Translator

This project implements a lightweight **Spanish to English** translation tool using basic natural language processing (NLP) techniques and evaluates translation quality using the **BLEU score**. It was built as part of an academic NLP assignment and demonstrates how machine translation can be done without relying on large-scale pretrained models.

---

## 📌 Project Overview

The goal of this project is to perform English translations of short Spanish sentences and evaluate translation performance using the BLEU metric. The project focuses on:

- Translating everyday Spanish phrases into English
- Cleaning and preprocessing the data
- Evaluating translation performance with BLEU scores
- Comparing predicted translations to reference translations

---

## ✨ Features

- 🔡 Custom Spanish-to-English translation logic
- 🧼 Preprocessing for punctuation and formatting issues
- 📏 Translation evaluation using BLEU score (via `nltk.translate`)
- 🧪 Includes both candidate and reference translations for comparison

---

📊 Example

# Candidate translation
"¿Cuánto cuesta la bolsa de caramelos?" → "How much is the bag of candy?"

# Reference translation
["How much does the bag of candy cost?"]

# BLEU score output
BLEU score: 0.72

---

🔧 Future Improvements
Add support for multi-sentence paragraphs

Integrate with Hugging Face transformers for higher-quality translations

Expand corpus and add evaluation beyond BLEU (e.g., METEOR, ROUGE)

Build a web or CLI interface for user input

---

🙋‍♀️ Author
Amber Gonzalez-Pacheco
MSBA Student @ UC Davis
