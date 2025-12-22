# Training-ML-Models-to-Demystify-Fake-Job-Postings

_A comparative study using BERT, ALBERT, ELECTRA (incoming), and RoBERTa (incoming) to identify fraudulent job postings_

## Problem Overview
Fake job postings are increasingly common on online job platforms, leaeding to:
- Wasted time and emotional stress for job seekers
- Financial scams and data exploitation
- Reduced trust in recruitment platforms
This project explores how modern NLP transformer models can be used to **detect fraudulent job postings based on textual signals**, helping job seeks and platforms identify suspicious listings earlier.

## Project Goal
- Build and evaluate machine learning models that classify job postings as **real or fraudulent**
- Compare the performance of multiple transformer-based architectures
- Understand how class imbalance and text characteristics affect model performance
This is an exploratory and research-driven project, most likely not production-grade

## Models Explored
- **BERT** = Baseline transformer for contextual text understanding
- **ALBERT** = Lightweight variant focusing on parameter efficiency
- **ELECTRA** = Discriminator-based pretraining, well-suited for classification tasks
Each model was fine-tuned on the same dataset to allow fair comparison across Precision, Recall, F1 score, and class-level performance (fraud vs non-fraud).
Special attention was given to **class imbalance**, which significantly impacts fraud detection tasks.

## Key Challenges
- **Severe class imbalance** (fraudulent posts are only about 5% of the dataset)
- High variance in job description length and structure
- Models achieving high accuracy but poor recall on the fraud class
- Transformer sensitivity to dataset size and noise
These challenges influence evaluation strategies that are still ongoing, which will affect interpretation of future results.

Stay tuned!
