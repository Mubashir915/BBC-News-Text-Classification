# BBC News Text Classification (Data Structures Project)

This repository contains a Machine Learning and Natural Language Processing (NLP) project developed to automate the classification of BBC News articles into distinct categories.

## Project Features
- **Web Scraping & Processing:** Text data combined from titles and descriptions.
- **Text Cleaning:** Done using NLTK (Stopwords removal, lowercase conversion, and punctuation cleaning).
- **Feature Extraction:** Implemented using `TfidfVectorizer` (Max features: 10,000).
- **Machine Learning Model:** Trained using a **Random Forest Classifier** (200 estimators).
- **Performance:** Achieved an outstanding average accuracy of **~99%**.

## Target Categories
- World
- Business
- Crime
- Technology
- General

## Files Included
- `main.py`: The complete Python pipeline containing text preprocessing, feature extraction, model training, and evaluation.
- `DS-Project-Report.docx`: Detailed academic project documentation including dataset structure and conclusions.
