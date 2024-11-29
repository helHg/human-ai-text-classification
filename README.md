# Human-AI Text Classification

This repository contains the code and resources for the **"Human-AI Text Classification"** project, conducted as part of the *COLING-2025 Workshop on MGT Detection Task 1 Public*. The project aimed to classify English text as either human-written or AI-generated, addressing challenges such as class imbalance and exploring fine-tuning strategies for large language models (LLMs).

The competition instructions can be found [here](https://github.com/mbzuai-nlp/COLING-2025-Workshop-on-MGT-Detection-Task1/tree/main).

## Repository Structure

- **`notebooks/`**: Jupyter notebooks for all models and experiments:
  - `mnb.ipynb`: Implementation of Multinomial Naive Bayes (MNB) with TF-IDF vectorization.
  - `roberta-baseline.ipynb`: Baseline RoBERTa implementation.
  - `customized-roberta.ipynb`: Customized RoBERTa with additional preprocessing and class-weighted loss.
  - `distil-roberta.ipynb`: Fine-tuning DistilRoBERTa with reduced training data.

## Best Results

| Model              | Accuracy | Precision | Recall  | F1-Macro | F1-Micro |
|--------------------|----------|-----------|---------|----------|----------|
| **Naive Bayes**    | 64.88%   | 62.38%    | 85.29%  | 62.39%   | 64.88%   |
| **Baseline RoBERTa** | 73.09% | 60.23%    | 97.99%  | 71.11%   | 73.09%   |
| **Customized RoBERTa** | 72.29% | 67.03% | 94.10%  | 70.00%   | 72.29%   |
| **DistilRoBERTa**  | **73.89%** | **68.22%** | **95.15%** | **71.80%** | **73.89%** |

---

This project was completed as part of the **COMP 6781 Statistical Natural Language Processing (Fall 2024)** course taught by **Professor Leila Kosseim** at Concordia University.
