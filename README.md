# Arabic Dialect Identification

This project explores the use of machine learning models to identify Arabic dialects using Natural Language Processing (NLP) techniques.

##  Data Collection and Preprocessing
The study uses two major datasets:
- **Integrated Arabic Dialects Dataset (IADD)**
- **Modern Arabic Dialect Corpus (MADAR)**

These datasets include a wide range of Arabic dialects. Preprocessing was crucial to ensure data quality and consistency, and it involved the following steps:

- **Up-sampling and Down-sampling**: Balanced the dataset by increasing underrepresented dialects and reducing overrepresented ones.
- **Text Normalization**: Standardized Arabic text by dediacritization (removal of diacritics) and normalization of spelling variations.
- **Cleaning**: Removed punctuation, digits, extra whitespace, and stop words to reduce noise.
- **Elongation Handling**: Reduced stretched or elongated Arabic words to their standard forms for consistency.
  
## Models Used
- Naive Bayes (baseline)
- Recurrent Neural Network (RNN)
- Long Short-Term Memory (LSTM)

##  Results
- **LSTM**: Accuracy 88%
- **Naive Bayes**: Accuracy 86%
- **RNN**: Accuracy 84%

##  Requirements
- Python
- scikit-learn
- TensorFlow / Keras
- pandas, numpy

##  Keywords
NLP, Arabic Dialects, Machine Learning, Text Classification, RNN, LSTM
