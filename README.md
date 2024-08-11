# GenAI Nanodegree Project 1: Apply Lightweight Fine-Tuning to a Foundation Model

Code walkthrough: [Notebook](<./Lightweight%20Fine-Tuning%20Foundation%20Model%20(deberta-v3).ipynb>)

## Task Overview

Classify whether the news is `real` (0) or `fake` (1). The dataset is from [HuggingFace](https://huggingface.co/datasets/mohammadjavadpirhadi/fake-news-detection-dataset-english).

## Model Overview

The model is the [deberta-v3](https://huggingface.co/microsoft/deberta-v3-base) from Microsoft.

## Fine-Tuning

The model is fine-tuned using QLoRA.

## Model Performance

- The original (non-fine-tuned) model has an accuracy of 53.6% on the test set.
- The fine-tuned model has an accuracy of 100% on the test set.
