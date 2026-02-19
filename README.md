# yolo_training_guide

A practical, end-to-end training guide for the YOLO family (YOLOv8 → YOLOv12):
dataset creation, labeling rules, training configuration, troubleshooting, and deployment-oriented best practices.

## What’s inside

### 1) Beginner visual guide (start here)
- **docs/BeginnerGuied.pdf**
- Explains how YOLO works using diagrams + simple analogies:
  backbone / neck / head, training vs inference, and real-world deployment intuition.

### 2) Main technical guide (from-scratch training + production mindset)
- **docs/MainTechnicalGuide-v1.1.pdf**
- Complete lifecycle guide for training YOLO detectors from random initialization (no pretrained weights):
  architecture selection (v8–v12), data requirements, sensor-specific strategy (thermal vs RGB),
  hardware/deployment guidance, and ML engineering practices (reproducibility, versioning, CI/CD, etc.).

### 3) YOLO12 Training Handbook (configuration reference)
- **docs/Train_Config_Hand_Book.pdf**
- Hyperparameter and training configuration reference for YOLO12 model family (n/s/m/l/x):
  definitions, recommended ranges, dependencies, quick cheatsheets, and troubleshooting.

### 4) Dataset creation & labeling tips
- **docs/8-tips-for-dataset-creation_01.pdf**
- Practical guidance for gathering and labeling datasets for object detection:
  camera/domain matching, diversity, avoiding near-duplicate frames, labeling rules, and incremental difficulty.

## Recommended reading order
1. BeginnerGuied.pdf  
2. 8-tips-for-dataset-creation_01.pdf  
3. MainTechnicalGuide-v1.1.pdf  
4. Train_Config_Hand_Book.pdf  
