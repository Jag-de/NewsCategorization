# Multiclass Document Classification Using LinearSVC and TF-IDF

ML project for classifying news articles into multiple categories using LinearSVC classifier and TF-IDF vectorization.

## Dataset

This project uses the **News Category Dataset** provided by AiresPucrs on Hugging Face 🤗 Datasets.

### Load Dataset
```python
from datasets import load_dataset

dataset = load_dataset("AiresPucrs/News-Category-Dataset")
