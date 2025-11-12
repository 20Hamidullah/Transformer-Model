# 🚀 Transformer Model for Text Classification

This repository contains a Jupyter notebook implementing a Transformer model for text classification tasks, focusing on sentiment analysis of movie reviews. 🎥📝

## 📚 Overview

The notebook covers:
- 🔍 **Attention Mechanism:** Step-by-step explanation and implementation of self-attention using token embeddings with scaled dot-product attention.
- 🧱 **Transformer Encoder:** A custom Keras layer implementing multi-head attention, layer normalization, dropout, and feed-forward networks.
- 📏 **Positional Encoding:** Implementation of sine and cosine positional encoding to incorporate order information into token embeddings.
- 🏗️ **Model Architecture:** Building a Transformer-based sentiment classifier with embedding layer, transformer encoder, global average pooling, dropout, and dense layers.
- ⚙️ **Training Preparation:** Preprocessing IMDB movie review dataset by loading, tokenizing, and padding sequences.
- 📊 **Model Summary and Sample Data:** Display of model parameters and example input sequences.

## 🛠️ Requirements

- Python 3.8+
- TensorFlow 2.x
- Keras
- NumPy
- Matplotlib (for visualization)
- scikit-learn (for train-test splitting)

## 🚀 Usage

1. Clone this repository.
2. Install required packages:

3. Run the notebook `Transformer.ipynb` in Jupyter Notebook or JupyterLab.
4. Follow the step-by-step explanations and code to understand Transformer attention and text classification.

## 🔗 References

This notebook is based on the tutorial:  
https://fall-2023-python-programming-for-data-science.readthedocs.io/en/latest/Lectures/Theme_3-Model_Engineering/Lecture_20-Transformer_Networks/Lecture_20-Transformer_Networks.html#20.1-Introduction-to-Transformers

## ✍️ Author

Developed by: Sayed Hamidullah Fazlly.

M. Sc. Web & Data Science (On-going), Koblenz, Germany

Email: 11hamidullah@gmail.com / sayedhamidullah@uni-koblenz.de

## 📄 License

This project is open source under the MIT License.
