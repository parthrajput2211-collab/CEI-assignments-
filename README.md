# CEI Assignments

This repository contains my weekly assignments completed during the **Celebal Technologies Internship**. Each week's work focuses on applying Data Science, Machine Learning, Deep Learning, NLP, and Generative AI concepts through practical assignments and hands-on implementation.

---

## Repository Structure

    CEI-Assignments/
    │
    ├── Week-1/
    │   └── week1_Parth_Rohilla_.ipynb
    │
    ├── Week-2/
    │   ├── week2_Parth_Rohilla_.ipynb
    │   └── tesla_deliveries_dataset_2015_2025.csv
    │
    ├── Week-3/
    │   ├── week3_Parth_Rohilla_.ipynb
    │   ├── Country-data.csv
    │   └── data-dictionary.csv
    │
    ├── Week-4/
    │   └── week4_Parth_Rohilla_.ipynb
    │
    ├── Week-5/
    │   └── week5_Parth_Rohilla_.ipynb
    │
    ├── Week-6/
    │   └── week6_Parth_Rohilla_.ipynb
    │
    ├── Week-7/
    │   ├── week7_Parth_Rohilla.ipynb
    │   └── Data_Science_Deep_Learning_Notes_for_RAG.pdf
    │
    ├── Week-8/
    │   ├── week8_Parth_Rohilla.ipynb
    │   └── week 8 quiz.pdf
    │
    ├── Final-Project/
    │   ├── MiniGPT_Parth_Rohilla.ipynb
    │   ├── minigpt_config.json
    │   ├── minigpt_model.pth
    │   ├── [dataset file]
    │   └── README.md
    │
    └── README.md

---

## Week 1

### Topics Covered
- Python Fundamentals
- NumPy
- Pandas
- Data Cleaning
- Data Manipulation

### Files
- `week1_Parth_Rohilla_.ipynb`

---

## Week 2

### Project
**End-to-End Machine Learning Pipeline on Tesla Sales & Price Data**

### Topics Covered
- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Linear Regression
- Random Forest Regression
- Hyperparameter Tuning using GridSearchCV
- Time Series Forecasting using ARIMA

### Files
- `week2_Parth_Rohilla_.ipynb`
- `tesla_deliveries_dataset_2015_2025.csv`

---

## Week 3

### Project
**Customer Intelligence System using Classification, Ensemble Learning & Clustering**

### Topics Covered
- Exploratory Data Analysis (EDA)
- Data Preprocessing
- Feature Scaling
- K-Means Clustering
- DBSCAN Clustering
- Principal Component Analysis (PCA)
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- XGBoost Classifier
- Model Evaluation
- Feature Importance

### Files
- `week3_Parth_Rohilla_.ipynb`
- `Country-data.csv`
- `data-dictionary.csv`

---

## Week 4

### Project
**Image Classification using ANN and CNN on CIFAR-10**

### Topics Covered
- Image Classification
- CIFAR-10 Dataset
- Artificial Neural Networks (ANN)
- Convolutional Neural Networks (CNN)
- Batch Normalization
- Dropout
- Data Augmentation
- Model Evaluation
- Confusion Matrix
- Classification Report
- ANN vs CNN Comparison

### Files
- `week4_Parth_Rohilla_.ipynb`

---

## Week 5

### Project
**Text Generation using RNN, LSTM and GRU**

### Topics Covered
- Text Preprocessing
- Tokenization
- Sequence Generation
- Word Embeddings
- Vanilla RNN
- LSTM
- GRU
- Text Generation
- Training Loss and Accuracy Comparison
- Model Parameter Comparison

### Files
- `week5_Parth_Rohilla_.ipynb`

---

## Week 6

### Project
**Image Denoising using Autoencoders on MNIST**

### Topics Covered
- MNIST Dataset
- Image Noise Generation
- Autoencoders
- Denoising Autoencoders
- Encoder and Decoder Architecture
- Fully Connected Autoencoder
- Convolutional Autoencoder
- Transposed Convolution
- Upsampling
- Image Reconstruction
- Mean Squared Error (MSE)
- Model Comparison

### Files
- `week6_Parth_Rohilla_.ipynb`

---

## Week 7

### Project
**Document Question Answering System using Retrieval-Augmented Generation (RAG)**

### Topics Covered
- PDF Text Extraction
- Text Chunking with Overlap
- Sentence Transformer Embeddings
- FAISS Vector Indexing and Semantic Retrieval
- Cross-Encoder Reranking
- Retrieval-Augmented Generation (RAG)
- Context Construction
- FLAN-T5 Answer Generation
- Multiple-Question Evaluation
- Retrieval and Context Inspection
- RAG Limitations and Improvements

### Files
- `week7_Parth_Rohilla.ipynb`
- `Data_Science_Deep_Learning_Notes_for_RAG.pdf`

---

## Week 8

### Project
**Single-Agent Smart Assistant – Agent Pipeline**

### Topics Covered
- Single-Agent Workflow
- Conditional Routing
- Tool Integration
- Calculator Tool
- Keyword Extractor Tool
- Structured JSON Output
- Input Validation
- Error Handling
- Sequential Tool Routing
- Multiple Query Testing
- Routing Evaluation

### Files
- `week8_Parth_Rohilla.ipynb`
- `week 8 quiz.pdf`

---

## Final Project

### Project
**MiniGPT – GPT-Style Language Model From Scratch**

### Overview

A small GPT-style decoder-only Transformer language model implemented from scratch using **PyTorch**.

The project focuses on understanding the fundamental components of the GPT architecture and training a small character-level language model from scratch.

### Topics Covered
- Character-Level Tokenization
- Language Modeling
- Token Embeddings
- Positional Embeddings
- Query, Key and Value
- Causal Self-Attention
- Multi-Head Attention
- Feed-Forward Networks
- Residual Connections
- Layer Normalization
- Transformer Blocks
- Decoder-Only Transformer Architecture
- Cross-Entropy Loss
- AdamW Optimizer
- Training and Validation
- Autoregressive Text Generation
- Bigram Language Model Baseline
- Bigram vs MiniGPT Comparison

### Model Training Results

| Metric | Initial Loss | Final Loss |
|---|---:|---:|
| Training Loss | 4.309 | 2.055 |
| Validation Loss | 4.315 | 2.093 |

The model showed a significant reduction in both training and validation loss, demonstrating that it successfully learned statistical patterns from the training corpus.

### Baseline Comparison

A simple **Bigram language model** was implemented as a baseline.

The Bigram model uses only the immediately preceding character for prediction, while MiniGPT uses causal self-attention to utilize a larger contextual window.

This comparison demonstrates the advantage of Transformer-based contextual language modeling over a simple Bigram approach.

### Files
- `MiniGPT_Parth_Rohilla.ipynb`
- `minigpt_config.json`
- `minigpt_model.pth`
- `[dataset file]`
- `README.md`

---

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Statsmodels
- TensorFlow
- Keras
- PyTorch
- OpenCV
- NLTK
- Sentence Transformers
- FAISS
- Hugging Face Transformers
- PyMuPDF
- Cross-Encoder
- FLAN-T5
- JSON
- Regular Expressions
- Git
- GitHub

---

## About

This repository is maintained as part of my internship learning journey at **Celebal Technologies**, showcasing weekly assignments and hands-on implementation of Data Science, Machine Learning, Deep Learning, NLP, and Generative AI concepts.

---

## Author

**Parth Rohilla**

GitHub: **https://github.com/parthrajput2211-collab**
