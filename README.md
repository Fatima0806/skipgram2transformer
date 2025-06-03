# SkipGram2Transformer: Word Embeddings & Neural Machine Translation from Scratch

This project demonstrates two fundamental Natural Language Processing (NLP) systems implemented from scratch using Python and PyTorch:

1. **Skip-Gram Word2Vec** — Learn word embeddings by implementing the Skip-Gram model with negative sampling manually using NumPy.
2. **Transformer-based Machine Translation** — Build a sequence-to-sequence translator with attention, using PyTorch’s Transformer module to translate English ↔ German.

---

## 📌 Project Highlights

### 🔹 Part 1: Skip-Gram Word2Vec (from scratch)
- Tokenizes and cleans input text
- Builds vocabulary and training pairs
- Implements forward and backward propagation using NumPy
- Trains on word co-occurrence data to learn word embeddings
- Visualizes embeddings using PCA

### 🔹 Part 2: Transformer for Translation (PyTorch)
- Implements tokenization, vocabulary building, and batching
- Constructs a full Transformer model (encoder-decoder)
- Trains the model on parallel English-German text
- Evaluates performance using BLEU score
- Visualizes training loss and BLEU improvements

---

## 📁 Dataset Information

The model uses the [Europarl v7 Parallel Corpus](http://www.statmt.org/europarl/):
- `europarl-v7.de-en.en`
- `europarl-v7.de-en.de`

📦 **Note:** Due to size limitations, the Europarl files are **not included** in this repository.  
You can download them manually from [statmt.org/europarl](http://www.statmt.org/europarl/).

After download, place them in your project root as:

/europarl-v7.de-en.en
/europarl-v7.de-en.de

Sample Output
Word Embeddings plotted using PCA (matplotlib)
Training Loss and BLEU Score plots after Transformer training
Translations printed and compared with reference

Learning Objectives
Understand word embedding generation through co-occurrence modeling
Learn sequence modeling using self-attention and positional encoding
Explore BLEU evaluation and training best practices for NMT

