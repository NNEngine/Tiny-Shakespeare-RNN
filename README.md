# Tiny Shakespeare RNN 

This project uses the **Tiny Shakespeare dataset** to train a recurrent neural network (RNN) for character-level text generation.  
The dataset consists of approximately 1 MB of Shakespeare's writings, preprocessed into plain text form.

---

## 📘 Dataset

**File:** `input.txt`  
**Source:** [Andrej Karpathy’s Tiny Shakespeare dataset](https://github.com/karpathy/char-rnn/blob/master/data/tinyshakespeare/input.txt)  
**License:** Public domain (original Shakespeare works) + MIT License (dataset compilation)

You are free to use, modify, and redistribute this dataset.  
If you use this dataset, please credit Andrej Karpathy for compiling it.

---

## 🧠 Model Overview
- Model type: Character-level RNN (or LSTM/GRU)
- Input: Individual characters
- Output: Predicted next character
- Objective: Learn the statistical structure of English text in Shakespeare’s style

