# Next Word Predictor using LSTM

This project implements a Next Word Prediction model using LSTM.

The model learns patterns from text data and predicts the next most likely word in a sentence.

---

## Concepts Covered

- Tokenization
- Text to sequence conversion
- N-gram sequence creation
- Padding sequences
- LSTM architecture
- Softmax classification over vocabulary
- Text generation

---

## Workflow

1. Load text dataset
2. Tokenize words
3. Create input-output sequence pairs
4. Pad sequences
5. Build LSTM model
6. Train model
7. Generate new text

---

## Model Architecture

- Embedding Layer
- LSTM Layer
- Dense Layer (Softmax)

Output dimension = vocabulary size

---

## Learning Outcome

After completing this notebook, you will understand:

- How language models work
- How LSTM handles sequential dependencies
- How text generation is implemented
- Foundation of modern LLMs

---

## Limitations

- Trained on small dataset
- Limited vocabulary
- Cannot capture very long dependencies

---

## Tech Stack

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib

