# Text Generation Project using Project Gutenberg Dataset

This project focuses on **text generation and analysis** using data sourced from the **Project Gutenberg** repository. It demonstrates techniques to process, clean, and analyze large text corpora for the purpose of natural language modeling and generation.

It showcases a pipeline that combines **text preprocessing**, **language modeling**, and **exploratory analysis** in Python using NLP and data science libraries.

---

## Project Overview

This project allows you to:

- Load and clean raw literary text from Project Gutenberg (e.g., *The Adventures of Sherlock Holmes*)
- Normalize text (e.g., lowercasing, stripping metadata)
- Perform exploratory analysis of text patterns
- Prepare data for language modeling
- Set up tokenization and sequence generation
- Build deep learning models to generate coherent text sequences

---

## Features

- Project Gutenberg text ingestion using file I/O
- Text normalization (lowercase, metadata removal)
- N-gram or sequence preparation for model input
- Tokenization and encoding using `Tokenizer`
- Text sequence padding and target shifting
- Future scope: RNN or Transformer-based language generation

---

## Technologies Used

### Core Libraries & Tools

- Python
- NumPy / Pandas
- TensorFlow / Keras (for model training)
- NLTK or Keras Tokenizer (for tokenization)
- Jupyter Notebooks (for development and visualization)

---

## Model Architecture (Planned / Optional)

- Embedding Layer (learned word vectors)
- LSTM / GRU / Transformer Layers (planned for sequence modeling)
- Dense Output Layer with Softmax for word prediction

> Currently, text extraction and preprocessing steps are implemented. Sequence modeling setup is the next milestone.

---

## Dataset

- **Source**: Project Gutenberg (https://www.gutenberg.org)
- **Sample Used**: *The Adventures of Sherlock Holmes* by Arthur Conan Doyle
- **File Format**: `.txt`
- **Path Example**: `/kaggle/input/projectgutenberg/book.txt`

---

## APIs / Integrations

- Project Gutenberg (manual download used)
- Tokenizer from `keras.preprocessing.text` (for encoding and sequence generation)
- TensorFlow / Keras (planned for deep learning-based generation)

---

## Author

**Krish Dua**  
Portfolio: https://krishdua.vercel.app  
LinkedIn: https://www.linkedin.com/in/krish-dua-9202a4272/

---
