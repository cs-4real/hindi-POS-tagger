# Hindi POS Tagger using NLTK and TnT (Trigram'n'Tag)

This project builds a Part-of-Speech (POS) tagger for **Hindi language** using NLTK's `TnT` (Trigrams'n'Tags) tagger trained on the Indian corpus provided by NLTK.

It also includes:

- Custom fallback heuristics to handle unknown (UNK) tokens
- Accurate tagging of Hindi punctuation like `।` and symbols like `|`
- Custom tokenization for Devanagari script to ensure correct sentence parsing
- Final model evaluation with fallback for improved accuracy

---

## 📦 Features

- ✅ Train POS tagger using Hindi corpus from NLTK's Indian dataset
- ✅ Fallback heuristic rules for unknown words (like verbs, conjunctions, auxiliaries)
- ✅ Custom tokenizer for Hindi (splits punctuation correctly)
- ✅ Accuracy evaluation using both TnT and fallback combined
- ✅ Handles special tokens like `|` and `।` as `SYM`

---

## 🛠 Installation

1. Make sure Python 3.x is installed.
2. Install required libraries:

```bash
pip install nltk
