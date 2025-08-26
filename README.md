# Duplicate Question Detection

## Overview
This project detects duplicate questions using Natural Language Processing (NLP) and Machine Learning techniques to improve search relevance on Q&A platforms.

## Dataset
- Source: Quora Question Pairs Dataset (or similar)
- Columns: Question1, Question2, and Label (1 for duplicate, 0 for non-duplicate)

## Workflow
### Data Preprocessing
- Text cleaning, tokenization, lemmatization
- Removal of stopwords and special characters

### Feature Engineering
- TF-IDF representation
- Word2Vec embeddings
- Fuzzy string similarity scores

### Model Training
- XGBoost and Random Forest classifiers
- Ensemble learning for improved accuracy
- Achieved 92% accuracy

## Installation
```bash
git clone https://github.com/username/duplicate-question-detection.git
cd duplicate-question-detection
pip install -r requirements.txt
# Parkinson-s-diseases_prediction
