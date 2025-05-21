# state-of-the-union-topic-modeling
Analyze U.S. Presidential State of the Union speeches from 1790 to 2012 using topic modeling techniques (LSI &amp; LDA) to uncover historical discourse trends.


# 🏛️ State of the Union Topic Modeling

This project analyzes the State of the Union speeches delivered by U.S. Presidents from 1790 to 2012 using advanced topic modeling techniques such as **Latent Semantic Indexing (LSI)** and **Latent Dirichlet Allocation (LDA)**. The goal is to extract dominant themes across history and track how discourse evolves over time.

## 📊 Project Overview

### 🔍 Objective
- Extract meaningful topics from historical U.S. Presidential speeches.
- Compare LSI and LDA topic modeling performance.
- Annotate and interpret topic trends across time and decades.

### 📁 Dataset
- Source: [State of the Union Speeches dataset]
- Contains speeches from **1790 to 2012**.
- Two columns: `Year`, `Speech`.

## 🧹 Data Preprocessing
- Lowercasing
- Number & punctuation removal
- Hyphen splitting
- Tokenization
- Stopword removal
- Lemmatization
- Rare word filtering (less than 2 occurrences)

## 🧠 Topic Modeling Methods

### 🔷 Latent Semantic Indexing (LSI)
- Vectorization using Bag-of-Words + TF-IDF.
- Dimensionality reduction via Singular Value Decomposition (SVD).
- Optimal topics selected using Coherence Score.
- Topics sampled and annotated with historical context.

### 🔶 Latent Dirichlet Allocation (LDA)
- Bayesian modeling assuming each document is a mixture of topics.
- Topics inferred based on word distributions.
- Decade-wise topic dominance analysis.

## 📈 Insights & Annotations
- Topic 5 (LSI): “War on Terror” most prominent in 1993.
- Topic 8 (LDA): “Technological & Economic Policy” peaked in 2010s.
- Thematic evolution from **economic/legal issues** to **technology & terrorism**.
- Decade-wise summaries reveal shifts in U.S. priorities and global challenges.

## 🔍 Comparison: LSI vs. LDA
| Feature       | LSI                       | LDA                          |
|---------------|----------------------------|-------------------------------|
| Basis         | Singular Value Decomposition | Bayesian Probabilistic Model |
| Performance   | Faster                     | More interpretable results   |
| Results       | Mixed interpretability     | Clearer, context-rich topics |



## 📚 References
- [Latent Semantic Analysis – Wikipedia](https://en.wikipedia.org/wiki/Latent_semantic_analysis)
- [Gensim Topic Modeling Examples](https://radimrehurek.com/gensim/auto_examples/core/run_topics_and_transformations.html)
- [Evaluate Topic Models Notebook](https://github.com/kapadias/medium-articles/blob/master/natural-language-processing/topic-modeling/Evaluate%20Topic%20Models.ipynb)

---

📬 *For questions or collaboration, feel free to open an issue or pull request.*
