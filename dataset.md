# Human vs AI Sentences Dataset

This project uses the **Human vs AI Sentences** dataset, which is available on **Hugging Face**.

The dataset consists of sentences labeled as:
- **Human-generated text** (label 1)
- **AI-generated text** (label 0)

### Accessing the Dataset

You can access the dataset using the Hugging Face `datasets` library with the following code:

```python
from datasets import load_dataset

# Load the dataset
dataset = load_dataset("shahxeebhassan/human_vs_ai_sentences")

