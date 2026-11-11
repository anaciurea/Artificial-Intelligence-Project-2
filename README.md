# Tema 2 — Inteligență Artificială: Clasificarea imaginilor cu rețele neurale

Clasificare de imagini pe două seturi de date:
- **„Vai de pielea mea”** — leziuni cutanate
- **„You're on candid camera”** — expresii faciale

## Conținut
| Fișier | Descriere |
|---|---|
| `Tema2-IA-Ciurea-Ana-Sorina-cod.ipynb` | Codul complet (PyTorch) |
| `Tema2-IA-Ciurea-Ana_Sorina-raport (1).pdf` | Raportul cu metodologie și rezultate |

## Ce include
- MLP și CNN antrenate de la zero, cu augmentări de date
- Tratarea dezechilibrului de clase (ponderi, `WeightedRandomSampler`)
- Fine-tuning ResNet-18 și MobileNet-v2, cu LR warmup
- Ablații: Dropout, BatchNorm, augmentări, dezechilibru, warmup
- Bonus: Curriculum Learning
- Generarea predicțiilor pentru Kaggle

## Rulare
```bash
pip install torch torchvision scikit-learn pandas numpy matplotlib seaborn pillow tensorboard
jupyter notebook Tema2-IA-Ciurea-Ana-Sorina-cod.ipynb
```
