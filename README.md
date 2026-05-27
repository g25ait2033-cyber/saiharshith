# saiharshith

# Goodreads Genre Classification with DistilBERT

This project fine-tunes a Hugging Face DistilBERT model to classify Goodreads book reviews into genre categories. Training was performed in a Kaggle Notebook using GPU acceleration, experiment tracking was done with Weights & Biases, evaluation results were saved as a W&B artifact, and the final trained model was pushed to Hugging Face Hub for reuse.

## Setup

Install dependencies:

```bash
pip install -r requirements.txt
```

Run inference using the trained Hugging Face model:

```bash
python inference.py
```

# Training Platform
Training was done on Kaggle Notebook using GPU T4 x2 acceleration and Kaggle Secrets for WANDB_API_KEY and HF_TOKEN.

Kaggle Notebook: https://www.kaggle.com/code/dsaiharshith/mlops-assignment2/notebook

# Results

| Metric    | Score |
|-----------|------:|
| Accuracy  | 0.60429  |
| F1 Score  | 0.60646 |
| Eval Loss | 2.15608 |


# Links
 - GitHub Repository: https://github.com/g25ait2033-cyber/saiharshith/
 - Hugging Face model: https://huggingface.co/g25ait2033-cyber/distilbert-goodreads-genres
 - W&B dashboard: https://wandb.ai/g25ait2033-prom-iit-rajasthan/mlops-assignment2
