# Hindi POS Tagger using NLTK TnT

This project implements a basic **Part-of-Speech (POS) tagger** for the Hindi language using the **TnT (Trigrams'n'Tags)** tagger from the NLTK library. It uses the pre-tagged Hindi corpus available in NLTK's Indian languages dataset.

---

## 📚 Overview

The TnT tagger is trained on the `hindi.pos` corpus, which includes POS-tagged sentences. The script:

- Loads and processes the tagged Hindi sentences
- Splits them into training and test sets
- Trains the TnT model
- Evaluates its accuracy
- Tags a custom input Hindi sentence

---

## 🚀 Getting Started

### Requirements

- Python 3.x
- NLTK library

### Installation

Install NLTK via pip if not already installed:

```bash
pip install nltk
