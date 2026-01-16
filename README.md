# CIFAR-10 Image Classification – ML Hiring Challenge

## Dataset
CIFAR-10 (60,000 images, 10 classes)

## Framework
- PyTorch
- torchvision
- Google Colab (GPU)

## Levels Completed
- Level 1: Baseline ResNet-18 (Test Accuracy: 92.16%)
- Level 2: Data Augmentation & Regularization (93.35%)
- Level 3: Model Explainability & Analysis
  `Used Grad-CAM to visualize class-discriminative regions`
  `Heatmaps highlight object-focused regions influencing predictions`
  `Confusion matrix shows strong diagonal dominance`
  `Minor confusion observed between visually similar classes (e.g., cat and dog)`
- Level 4: Ensemble Learning
`Trained multiple deep learning models:
   ResNet-18
   ResNet-34
   EfficientNet-B0
  Used majority voting to combine predictions
  Ensemble reduced variance and improved robustness
  Final Ensemble Test Accuracy: 96.09%`



## Files
- `lvl1ml.pdf`: Colab Containing Level 1 Code
- `Untitled9.ipynb`: Colab notebook containing Level 2 code
- `Level 3.ipynb`: Colab notebook containing Leve 3 code
- `lvl4cefar10.ipynb`: olab notebook containing Leve 4 code

## How to Run
Open the notebook in Google Colab and run all cells top to bottom.

## Notes
This repository is part of a multi-level ML hiring assessment.
