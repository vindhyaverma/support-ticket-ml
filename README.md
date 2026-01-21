# support-ticket-ml
# Support Ticket Classification & Prioritization (ML Task 2)

## Project Overview
This project builds a Machine Learning system to automatically classify and prioritize customer support tickets.  
The system helps support teams understand ticket type and urgency without manual sorting.

## Business Problem
Support teams receive thousands of tickets daily:
- Tickets are not categorized properly
- Urgent issues get delayed
- Time is wasted on manual triaging

This system solves the problem by automatically:
- Classifying tickets into categories
- Assigning priority levels (High / Medium / Low)

## Dataset
- Source: IT Support Ticket Dataset
- Total Tickets: 47,837
- Columns:
  - `Document` – ticket text
  - `Topic_group` – issue category

## Text Preprocessing
- Lowercasing
- Punctuation removal
- Tokenization
- Stopword removal
- Clean text generation

## Feature Engineering
- TF-IDF Vectorization
- Unigrams and Bigrams
- Max features: 5,000

## Models Used
- Logistic Regression (Category Classification)
- Logistic Regression (Priority Prediction)

## Evaluation Results
- Category Classification:
  - Weighted F1-Score: ~0.82
- Priority Classification:
  - High Priority F1: ~0.84
  - Medium Priority F1: ~0.84
  - Low Priority F1: ~0.78

## Example Prediction
Input:
"My system is not working and I cannot login"

Output:
- Category: Hardware
- Priority: High

## Impact
This system:
- Reduces ticket backlog
- Improves response time
- Helps support teams focus on urgent issues

## Tech Stack
- Python
- Pandas
- NLTK
- Scikit-learn
- Jupyter Notebook

## Author
Built as part of **Future Interns – Machine Learning Task 2 (2026)**
