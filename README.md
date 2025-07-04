# parkinsons-multimodal-ml-dl
Multimodal machine learning for Parkinson’s Disease: Gait, Voice, and MRI analysis with ensemble/fusion models. Includes feature extraction, model training, and stacking/fusion meta-classification in Python/Jupyter.

# Parkinson’s Multimodal ML

This repository implements multimodal machine learning for Parkinson’s Disease detection using Gait, Voice, and MRI data.  
It covers feature extraction, model training, and ensemble/fusion meta-classification in Python/Jupyter.

## Features

- **Gait Analysis:** Feature extraction and XGBoost model training from raw sensor data
- **Voice Analysis:** Feature engineering, stacking ensemble (XGBoost, RF, LR), advanced preprocessing
- **MRI Analysis:** Deep learning and classical ML for MRI image classification
- **Fusion Model:** Meta-classifier that combines predictions from all modalities

## Files

- `MRI.ipynb` — MRI feature extraction, CNN, evaluation
- `GAIT.ipynb` — Gait feature extraction, XGBoost model, evaluation
- `Voice.ipynb` — Voice feature engineering, stacking classifier, evaluation
- `Fusion_Model.ipynb` — Fusion/ensemble meta-classification combining all modalities
