# ✍️ Next Word Prediction Using LSTM

<img src="https://github.com/priyanshu-sen-07/next-word-prediction-lstm/blob/main/Screenshot%202025-07-13%20000207.png" width="700"/>

## 📖 Project Overview

This project builds a deep learning model capable of predicting the **next word** in a given input sequence. Using the powerful **LSTM (Long Short-Term Memory)** network architecture, the model is trained on Shakespeare’s *Hamlet* to learn word patterns and context.

A clean and interactive **Streamlit web app** allows users to test the model in real-time.

---

## ⚙️ Key Features

- Predicts the next word given an input phrase
- Trained on classic literature for rich language context
- Real-time predictions via a user-friendly Streamlit interface
- LSTM-based architecture for better memory of word sequences

---

## 🔍 Project Pipeline

### 1. 📚 Data Collection
- Dataset: Full text of *Hamlet* by William Shakespeare
- Source: Public domain literary text

### 2. 🧹 Data Preprocessing
- Tokenization of text
- Creation of input-output word sequences
- Sequence padding for uniform input lengths
- Split into training and test sets

### 3. 🏗️ Model Architecture
- **Embedding Layer**: Converts tokens into dense vectors
- **2 LSTM Layers**: Captures sequential dependencies
- **Dense Softmax Output Layer**: Predicts the next word probability

### 4. 🧠 Model Training
- Uses **categorical cross-entropy** loss
- Optimizer: **Adam**
- **Early stopping** to avoid overfitting based on validation loss

### 5. 🧪 Model Evaluation
- Tested using custom input phrases
- Evaluated on its ability to predict semantically correct next words

### 6. 🌐 Streamlit App Deployment
- User enters a sentence
- Model predicts and displays the next word
- Real-time and minimalistic web interface

---

## 🛠️ Technologies Used

- `Python`
- `TensorFlow` / `Keras`
- `NumPy`, `Pandas`
- `Streamlit`
- `Natural Language Processing (NLP)`

---
