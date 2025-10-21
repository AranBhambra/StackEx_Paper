# StackEx_Paper
# Stack Exchange Topic Modeling: Economic Discussions During COVID-19

**Author:**   
**Repository purpose:** Supplementary outputs and visualizations for the paper  
> *“Exploring Economic Stream and Sentiment Shifts on Stack Exchange During the COVID-19 Pandemic.”*

---

## 📘 Overview

This repository contains code, processed data, and interactive visualizations used in the analysis of topic modeling on Stack Exchange platforms across three time periods—**pre-COVID**, **during-COVID**, and **post-COVID**.  
The study investigates how discussions related to **economic themes and sentiment** evolved during the pandemic using **Natural Language Processing (NLP)** and **machine learning** techniques.

### Research Summary
The study analyzes Stack Exchange user content to uncover:
- Shifts in public engagement with economic topics across pandemic phases.
- How economic sentiment evolved in response to global disruptions.
- The adaptability of online platforms in shaping digital economic discourse.

---

## 🧠 Methodology

The textual data was processed using three different word embedding approaches:

| Embedding Type | Description |
|----------------|-------------|
| **Unigram Bag of Words** | Standard frequency-based representation of single terms. |
| **Bigram Bag of Words** | Captures frequent two-word phrases (context-aware). |
| **TF-IDF** | Weights terms by importance across the corpus. |

Each embedding was used as input for **three topic modeling algorithms**:

| Topic Modeling Method | Description |
|------------------------|-------------|
| **LDA (Latent Dirichlet Allocation)** | Probabilistic model discovering word-topic distributions. |
| **NMF (Non-Negative Matrix Factorization)** | Matrix decomposition approach producing interpretable topic clusters. |
| **BERTopic** | Transformer-based model using contextual embeddings for topic discovery. |

The outputs were generated for each combination of:
- **3 embedding techniques**
- **3 pandemic phases**: pre-, during-, and post-COVID
- **3 topic modeling algorithms**

Total combinations: **27 topic model outputs**
