# Disaster-Tweet-Classification-NLP Project

# Disaster Tweet Classification (NLP Project)


This project was part of my Data Science & AI course. The goal was to classify tweets as real disaster-related or not using an end-to-end NLP pipeline.

## Methods Used
- **Text Cleaning** with spaCy
- **Features**: 
  - TF-IDF (sparse)
  - Sentence-BERT (dense)
- **Models**:
  - Naive Bayes (with TF-IDF)
  - Logistic Regression (with both TF-IDF and BERT)

## Results
Logistic Regression performed best overall. BERT features gave better accuracy than TF-IDF but were slower.

- TF-IDF is fast and easy to interpret.
- Sentence-BERT gives deeper meaning but needs more resources.
- Logistic Regression worked better than Naive Bayes.
