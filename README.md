# Movie Review Sentiment Analysis

This repository contains the implementation of a **Sentiment Analysis** project developed as part of the *Text Mining for Data Science* course at ISCTE — University Institute of Lisbon.

The project focuses on **sentiment classification in textual data**, exploring multiple approaches ranging from lexicon-based and rule-based techniques to advanced **machine learning** and **transformer-based models**.

---

## Repository Structure

| File | Description |
|------|-------------|
| `2.2.ipynb` | Evaluation of existing sentiment analysis tools (**TextBlob** and **VADER**) on the IMDB Reviews dataset. Establishes an initial performance baseline. |
| `2.3.ipynb` | Implementation of a lexicon-based classifier using **NRC EmoLex**, including text preprocessing and negation handling. |
| `2.4.ipynb` | Training of supervised machine learning models (**Logistic Regression + TF-IDF**) with different preprocessing strategies. |
| `2.5.ipynb` | Application of transformer-based models (**DistilBERT**): use of pre-trained pipelines and manual fine-tuning using PyTorch. |
| `2.6.ipynb` | Use of **generative models** for sentiment analysis in Portuguese, including evaluation of multilingual models and zero-shot learning techniques. |
| `clean_NCR.py` | Script for cleaning the **NRC EmoLex** lexicon, extracting only the necessary columns (`word`, `positive`, `negative`) for pipeline integration. |

---

## Methods Explored

- Lexicon-based Sentiment Analysis  
- Rule-based Approaches  
- Traditional Machine Learning (TF-IDF + Logistic Regression)  
- Transformer Models (DistilBERT)  
- Fine-tuning with PyTorch  
- Generative AI for Text Classification  
- Zero-shot Learning  
- Multilingual NLP  

---

## Project Objective

To compare different sentiment analysis strategies and evaluate how performance evolves from rule-based systems to modern deep learning and generative AI approaches.

---
