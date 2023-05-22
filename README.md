## medical-ner-python
#Python Medical NER: Detecting Medical Entities in Text.

This repository contains a Python script for performing Medical Named Entity Recognition (NER). The script uses natural language processing (NLP) techniques and machine learning to identify and classify medical entities, such as drugs, diseases, symptoms, and tests, in text.

The code reads a JSON file containing medical text examples, tokenizes the words, applies Part-of-Speech (POS) tagging, and preprocesses the sentences by removing stop words and lemmatizing words. It then applies a set of predefined patterns to detect entities in the sentences. The detected entities are labeled, and a linear support vector classifier is trained to predict entity labels based on feature vectors derived from the sentences.

## Key Features:
- Tokenization, POS tagging, and preprocessing of medical text
- Detection and classification of medical entities using predefined patterns
- Training a linear support vector classifier for entity recognition
- Evaluation of the classifier's performance using precision, recall, and F1-score metrics

## Usage:
1. Install the required packages (NLTK and scikit-learn) using pip.
2. Prepare a JSON file (e.g., medical_ner.json) containing medical text examples.
3. Run the script, providing the path to the JSON file as input.
4. The script will tokenize the text, detect and label medical entities, train a classifier, and output evaluation metrics.

Contributions, bug reports, and feature requests are welcome! Feel free to fork the repository, make improvements, and submit pull requests.

## License

This project is not licensed, and all rights are reserved. You are not permitted to use, modify, or distribute the code without explicit permission.

## Contributors:
- Omar Shatla: Code development and implementation.
- Rewan Noor: Presentation slides preparation and project support.
