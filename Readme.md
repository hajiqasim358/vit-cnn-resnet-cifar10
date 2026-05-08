# Comparative Analysis of Vision Transformer, Hybrid CNN, and Transfer Learning-Based ResNet for CIFAR-10 Image Classification

## Overview

This project presents a comparative study of three deep learning architectures for image classification on the CIFAR-10 dataset:

- Vision Transformer (ViT)
- Hybrid CNN-MLP Model
- Transfer Learning-Based ResNet18

The models were implemented and evaluated using PyTorch under a unified experimental framework. Performance was compared using accuracy, precision, recall, F1-score, confusion matrices, and training behavior analysis.

An IEEE-format research paper is also included, documenting the methodology, experiments, results, and conclusions of the study.

---

## Models Implemented

### Vision Transformer (ViT)
A transformer-based architecture implemented from scratch using:
- Patch embedding
- Positional encoding
- Multi-head self-attention
- Transformer encoder blocks

### Hybrid CNN-MLP
A hybrid architecture combining:
- Convolutional layers for feature extraction
- Multi-Layer Perceptron (MLP) for classification

### Transfer Learning-Based ResNet18
A pretrained ResNet18 model fine-tuned on CIFAR-10 using:
- Transfer learning
- Partial layer unfreezing
- ImageNet preprocessing and normalization

---

## Dataset

- CIFAR-10 Dataset
- 60,000 RGB images
- 10 image classes
- Image size: 32×32

Classes:
- Airplane
- Automobile
- Bird
- Cat
- Deer
- Dog
- Frog
- Horse
- Ship
- Truck

---

## Evaluation Metrics

The models were evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- Training and Validation Loss
- Training and Validation Accuracy

---

## Results

| Model | Accuracy |
|-------|----------|
| Vision Transformer (ViT) | 72.41% |
| Hybrid CNN-MLP | Higher than ViT |
| ResNet18 (Transfer Learning) | Best Overall Performance |

### Key Findings
- ViT captured global contextual relationships but required more data for optimal learning.
- Hybrid CNN achieved stable convergence and balanced performance.
- ResNet18 produced the highest classification accuracy due to transfer learning and pretrained feature extraction.

---

## Technologies Used

- Python
- PyTorch
- Torchvision
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Repository Structure

```text
.
├── notebook.ipynb
├── paper/
│   ├── paper.pdf
│   ├── paper.tex
│   └── references.bib
├── requirements.txt
├── README.md
└── .gitignore
```

---

## How to Run

### Clone Repository

```bash
git clone <repository-link>
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Notebook

```bash
jupyter notebook
```

---

## Paper

The complete IEEE-format research paper is available in the `paper/` directory, including:
- PDF version
- LaTeX source
- BibTeX references

---

## Author

**Haji Qasim**

LinkedIn:  
www.linkedin.com/in/hajiqasim358