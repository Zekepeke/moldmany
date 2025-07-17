# moldmany  
A simple character-level language model that learns to mold... many.

Inspired by Andrej Karpathy
---

## What It Does
- Loads a dataset of names (or any text corpus)
- Builds a vocabulary from unique characters
- Computes character-to-character transition probabilities
- Samples brand new "names" using a Bigram model
---

## 🧠 Model Overview

This project uses a **Bigram model**, which:
- Treats each character as conditionally dependent on just the previous character
- Uses a simple counts-to-probabilities matrix (no deep learning frameworks yet!)
- Captures basic statistical structure in a text corpus

---

## 🏗 Example

**Training on simple names dataset:**

Input: ['emma', 'noah', 'liam', 'olivia']
Output: 'nolia', 'olmah', 'emvia', ...

Sometimes there is a gem, sometimes you get gibberish but it's all part of the game.