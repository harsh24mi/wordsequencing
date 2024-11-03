# wordsequencing
# Bigram-based Term Classification

> A simple Python project to classify terms using a bigram-based multi-hot encoding and a decision tree classifier.

## Table of Contents
1. [Overview](#overview)
2. [Features](#features)
3. [Requirements](#requirements)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Code Explanation](#code-explanation)
7. [Future Improvements](#future-improvements)
8. [License](#license)

---

### Overview
This project implements a text classification model that classifies terms based on their bigram structure using a decision tree classifier. It extracts bigrams (two-character combinations) from each term, generates multi-hot encoded vectors representing these bigrams, and trains a decision tree model to classify terms based on these features.

### Features
- **Bigram Extraction**: Extracts bigrams from input terms.
- **Multi-hot Encoding**: Encodes terms into binary vectors based on the presence of unique bigrams.
- **Decision Tree Classification**: Uses a decision tree to classify terms based on their bigram patterns.
- **Custom Predictions**: Predicts terms based on a new set of bigrams provided by the user.

### Requirements
- Python 3.x
- `numpy`
- `scikit-learn`

### Installation
1. **Clone the Repository**
    ```bash
    git clone https://github.com/your-username/bigram-term-classification.git
    cd bigram-term-classification
    ```

2. **Install Dependencies**
    ```bash
    pip install numpy scikit-learn
    ```

### Usage
1. **Define Terms**
   Define a list of terms to be classified. For example:
   ```python
   terms = ["hello", "world", "help", "hold", "whole"]
