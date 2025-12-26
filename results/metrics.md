# Model Evaluation Metrics

## Model Type
Fully Connected Neural Network for handwritten digit recognition (0–9).

## Training Configuration
- Number of Epochs: 10
- Batch Size: 32
- Optimizer: Adam
- Loss Function: Categorical Crossentropy
- Validation Split: Used during training

## Training Performance (Per Epoch)

| Epoch | Training Accuracy | Training Loss | Validation Accuracy | Validation Loss |
|------|-------------------|---------------|---------------------|-----------------|
| 1 | 0.8435 | 0.5398 | 0.9460 | 0.1760 |
| 2 | 0.9611 | 0.1308 | 0.9623 | 0.1185 |
| 3 | 0.9733 | 0.0848 | 0.9655 | 0.1114 |
| 4 | 0.9799 | 0.0624 | 0.9676 | 0.1022 |
| 5 | 0.9858 | 0.0469 | 0.9689 | 0.1022 |
| 6 | 0.9894 | 0.0338 | 0.9686 | 0.1080 |
| 7 | 0.9919 | 0.0285 | 0.9696 | 0.1132 |
| 8 | 0.9916 | 0.0276 | 0.9676 | 0.1148 |
| 9 | 0.9932 | 0.0200 | 0.9725 | 0.1064 |
| 10 | 0.9946 | 0.0170 | 0.9707 | 0.1187 |

## Final Model Evaluation on Validation Data
- Validation Accuracy: **97.07%**
- Validation Loss: **0.1352**

All metrics listed above are directly obtained from the execution outputs
shown in the Jupyter Notebook.
