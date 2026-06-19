# Week 6 — Word Embeddings & Semantic Similarity (JurisAI Court Vocabulary)

## Overview

This week focuses on **word embeddings** using the Word2Vec model applied to a legal/court document dataset. The task explores how words in a legal context relate semantically and visualizes those relationships using PCA-based cluster plots.

## Contents

| File | Description |
|------|-------------|
| [01_Source code.ipynb](01_Source%20code.ipynb) | Word2Vec model training, one-hot encoding comparison, similarity analysis, and PCA visualization |
| [02_Courtsentences.ipynb](02_Courtsentences.ipynb) | Court sentence dataset export to JSON and TXT formats |
| [03_Similarity analysis report.docx](03_Similarity%20%20analysis%20report.docx) | Written report on the similarity analysis findings |
| [04_Visualization screenshots/](04_Visualization%20screenshots/) | PCA scatter plot screenshots of word embedding clusters |

## Key Concepts Covered

- **One-Hot Encoding** vs **Word Embeddings** — comparing sparse vs dense word representations
- **Word2Vec** (Gensim) — training on anonymized court sentences with `vector_size=50`, `window=3`
- **Cosine Similarity** — measuring semantic closeness between legal terms (e.g. `court`, `judge`, `plaintiff`, `defendant`)
- **PCA Visualization** — reducing 50-dimensional word vectors to 2D to visualize word clusters

## Dataset

A custom anonymized court document dataset of 15 sentences covering legal vocabulary:
`court`, `judge`, `plaintiff`, `defendant`, `appeal`, `judgment`, `evidence`, `ruling`, `lawyer`, `magistrate`, `witness`, `prosecution`

## Visualizations

### Word Embedding Clusters — Mini Dataset
![Word Embeddings Mini](04_Visualization%20screenshots/Screenshot%202026-06-19%20083129.png)

![Word Embeddings Mini 2](04_Visualization%20screenshots/Screenshot%202026-06-19%20083146.png)

### Word Embedding Clusters — Expanded JurisAI Court Vocabulary
![Word Embeddings Expanded](04_Visualization%20screenshots/Screenshot%202026-06-19%20083217.png)

![Word Embeddings Expanded 2](04_Visualization%20screenshots/Screenshot%202026-06-19%20083236.png)
