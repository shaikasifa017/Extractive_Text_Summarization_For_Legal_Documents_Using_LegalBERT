# Extractive_Text_Summarization_For_Legal_Documents_Using_LegalBERT

## Overview

This project presents an extractive text summarization system for Indian legal judgments. The objective is to generate concise summaries by identifying and selecting the most important sentences from lengthy legal documents while preserving key legal information.

## Features

* Legal domain-specific sentence representations using LegalBERT
* Knapsack Optimization for selecting the most informative sentences
* Legal structure-aware filtering to improve summary quality
* Redundancy reduction and enhanced coherence
* Support for both supervised and unsupervised evaluation approaches

## Methodology

1. Preprocess legal judgments and split them into sentences.
2. Generate contextual sentence embeddings using LegalBERT.
3. Rank sentences based on importance scores.
4. Apply Knapsack Optimization to select sentences under length constraints.
5. Generate extractive summaries from the selected sentences.

## Evaluation

### Unsupervised Evaluation

* Kendall's Tau
* Kendall's p-value
* Spearman Correlation
* Top-K Precision
* Top-K Recall
* Top-K F1 Score

### Supervised Evaluation

* ROUGE-1
* ROUGE-2
* ROUGE-L

## Tech Stack

* Python
* LegalBERT
* Transformers
* NumPy
* Pandas
* Scikit-learn
* NLTK

## Results

The proposed approach effectively identified important legal content, producing concise summaries with improved relevance and reduced redundancy compared to baseline extractive methods.

