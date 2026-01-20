# customer-support-ticket-ml
Customer support ticket classification and entity extraction using NLP

## Project Overview
This project builds a traditional Machine Learning pipeline to analyze customer
support tickets. The system predicts issue type and urgency level and extracts
important entities from ticket text.

## Dataset
The dataset (dataset1.xls) contains ticket_id, ticket_text, issue_type,
urgency_level, and product columns.

## Preprocessing
- Lowercasing text
- Removing punctuation and numbers
- Tokenization
- Stopword removal
- Lemmatization
- Handling missing values

## Feature Engineering
- TF-IDF vectorization
- Ticket length
- Sentiment score using VADER

## Models
Two Logistic Regression models were trained:
1. Issue Type Classifier
2. Urgency Level Classifier

## Evaluation
- Classification report
- Confusion matrices
- 5-fold cross-validation

## Entity Extraction
Rule-based extraction of:
- Product names
- Dates
- Complaint keywords

## Gradio App
A Gradio web interface allows users to input or select ticket text and view predictions.

## How to Run
1. Install required libraries
2. Run all notebook cells
3. Launch the Gradio app

## Limitations
- Rule-based entity extraction
- Traditional ML models only

## Try app at https://dc20e9e9a1abf3c2b5.gradio.live/
