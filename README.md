# Mobile UI Screen Classification Using Vision Transformers

## Project Overview

This project aims to develop a mobile UI screen classification system using a pretrained Vision Transformer (ViT) fine-tuned on the Enrico dataset.

The system classifies mobile application screenshots into their corresponding design-topic categories.

## Objectives

- Prepare and inspect the Enrico dataset.
- Fine-tune a pretrained Vision Transformer for image classification.
- Evaluate the model using standard classification metrics.
- Develop a demonstration application for screenshot classification.

## Dataset

**Enrico Dataset**

- 1,460 mobile UI screenshots
- 20 design-topic categories
- Screenshot resolution: 540 × 960 pixels

Source: https://github.com/luileito/enrico

## Model Architecture

Pretrained Vision Transformer (ViT), using the `google/vit-base-patch16-224` checkpoint.

## Technologies

- Python
- PyTorch
- Hugging Face Transformers
- Google Colab
- Scikit-learn
- Matplotlib

## Project Structure

```text
mobile-ui-screen-classification/
├── notebooks/
│   └── mobile_ui_screen_classification.ipynb
├── README.md
└── requirements.txt
```

## Project Status

Currently in development. Dataset inspection and preparation are underway.

## Team

Add the names of all project members here.
