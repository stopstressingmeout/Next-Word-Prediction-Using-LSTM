# 🧠 Next Word Prediction using LSTM (PyTorch)

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![PyTorch](https://img.shields.io/badge/PyTorch-Deep%20Learning-red?logo=pytorch)
![NLP](https://img.shields.io/badge/NLP-Next%20Word%20Prediction-green)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

A beginner-friendly Natural Language Processing (NLP) project that builds a **Next Word Prediction** model from scratch using **PyTorch** and **Long Short-Term Memory (LSTM)** networks.

The project demonstrates the complete deep learning workflow—from text preprocessing and vocabulary creation to training an LSTM model capable of predicting the next word in a sentence.

---

## 📌 Project Overview

Language models learn patterns in text by predicting the most probable next word given a sequence of previous words.

In this project, I implemented an end-to-end LSTM-based language model using PyTorch without relying on high-level NLP frameworks.

The notebook covers:

- Text preprocessing
- Tokenization
- Vocabulary creation
- Sequence generation
- Dataset preparation
- LSTM model implementation
- Model training
- Accuracy evaluation
- Next-word prediction

---

## 🚀 Features

- Text preprocessing and normalization
- Tokenization using NLTK
- Vocabulary generation
- Word ↔ Index mapping
- Sequence padding
- Custom PyTorch Dataset
- DataLoader implementation
- LSTM neural network
- CrossEntropyLoss
- Adam optimizer
- Model evaluation
- Interactive next-word prediction

---

## 🛠️ Tech Stack

- Python
- PyTorch
- NLTK
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

---

## 🧠 Model Architecture

```
Input Text
      │
      ▼
Tokenization
      │
      ▼
Vocabulary Creation
      │
      ▼
Sequence Generation
      │
      ▼
Embedding Layer
      │
      ▼
LSTM Layer
      │
      ▼
Fully Connected Layer
      │
      ▼
Predicted Next Word
```

---

## ⚙️ Training Configuration

| Parameter | Value |
|-----------|------:|
| Embedding Dimension | 100 |
| Hidden Dimension | 150 |
| Optimizer | Adam |
| Learning Rate | 0.001 |
| Loss Function | CrossEntropyLoss |
| Epochs | 50 |

---

## 📈 Results

| Metric | Value |
|---------|------:|
| Training Accuracy | **96.94%** |

> **Note:** The reported accuracy is calculated on the training dataset. It demonstrates how effectively the model learned the provided corpus and should not be interpreted as generalization performance on unseen text.

---

## 🔄 Workflow

```
Raw Text
   │
   ▼
Cleaning
   │
   ▼
Tokenization
   │
   ▼
Vocabulary Building
   │
   ▼
Sequence Generation
   │
   ▼
Padding
   │
   ▼
Dataset & DataLoader
   │
   ▼
LSTM Training
   │
   ▼
Model Evaluation
   │
   ▼
Next Word Prediction
```

---

## 💻 Example

Input

```
Artificial intelligence is
```

Prediction

```
transforming
```

*(Prediction depends on the training text.)*

---

## 📚 Learning Outcomes

Through this project I gained practical experience with:

- Natural Language Processing fundamentals
- Word embeddings
- Sequence modeling
- LSTM networks
- Building custom PyTorch datasets
- Model training and evaluation
- Language model inference

---

## 📁 Repository Structure

```
Next-Word-Prediction-LSTM/
│
├── whole_lstm_project.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

---

## 🔮 Future Improvements

- Train on a larger corpus
- Add Dropout regularization
- Save and load trained models
- Implement GRU architecture
- Compare with Transformer models
- Predict multiple words instead of a single word
- Deploy using Streamlit

