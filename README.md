# Artificial Intelligence — Assignment 2: Image Classification with Neural Networks

Image classification on two datasets:
- **"Vai de pielea mea"** — skin lesions
- **"You're on candid camera"** — facial expressions

## Contents
| File | Description |
|---|---|
| `Tema2-IA-Ciurea-Ana-Sorina-cod.ipynb` | Full source code (PyTorch) |
| `Tema2-IA-Ciurea-Ana_Sorina-raport (1).pdf` | Report with methodology and results |

## What's included
- MLP and CNN models trained from scratch, with data augmentation
- Class imbalance handling (class weights, `WeightedRandomSampler`)
- Fine-tuning of ResNet-18 and MobileNet-v2, with LR warmup
- Ablation studies: Dropout, BatchNorm, augmentations, class imbalance, warmup
- Bonus: Curriculum Learning
- Prediction generation for Kaggle submission

## How to run
pip install torch torchvision scikit-learn pandas numpy matplotlib seaborn pillow tensorboard
jupyter notebook Tema2-IA-Ciurea-Ana-Sorina-cod.ipynb
