# 🌾 Rice Leaf Disease Detection Using Deep Learning Models

A deep learning-based rice leaf disease classification system developed as part of the MBKM-BRIN Research Program. This project investigates and compares multiple transfer learning architectures for automated plant disease detection using image-based classification.

## Highlights

- Comparative study of five deep learning architectures
- Transfer learning implementation using pretrained models
- Comprehensive evaluation using classification metrics
- Data augmentation for improved generalization
- Application in smart agriculture and precision farming

## Models Evaluated

| Model | Architecture Type |
|---------|---------|
| VGG16 | CNN |
| VGG19 | CNN |
| ResNet50V2 | Residual CNN |
| InceptionResNetV2 | Hybrid Inception-Residual Network |
| YOLOv8 Classification | Modern Vision Architecture |

---

## Dataset

The dataset consists of rice leaf images representing multiple disease categories and healthy leaf conditions. Images are divided into training, validation, and testing subsets to ensure robust model evaluation.

### Sample Pipeline

```text
Dataset
   ↓
Preprocessing
   ↓
Data Augmentation
   ↓
Transfer Learning
   ↓
Model Training
   ↓
Evaluation
   ↓
Performance Comparison
```

---

## Methodology

### Data Preprocessing

- Image resizing
- Pixel normalization
- Label encoding
- Dataset splitting

### Data Augmentation

- Brightness adjustment
- Saturation adjustment
- Random grayscale conversion
- Additional image transformations

### Transfer Learning

Pretrained weights are used to accelerate convergence and improve feature extraction capabilities.

---

## Evaluation Metrics

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Classification Report

---

## Technology Stack

| Category | Tools |
|-----------|---------|
| Language | Python |
| Deep Learning | TensorFlow, Keras, KerasCV |
| Data Analysis | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Machine Learning Utilities | Scikit-Learn |

---

## Project Structure

```text
Rice-Leaf-Disease-Detection/
│
├── dataset/
├── notebooks/
│   └── rice_leaf_disease_detection.ipynb
├── models/
├── results/
│   ├── confusion_matrix/
│   ├── training_curves/
│   └── classification_reports/
├── README.md
└── requirements.txt
```

---

## Research Contribution

This project contributes to the development of:

- Smart Agriculture
- Precision Farming
- Plant Disease Monitoring
- Computer Vision Applications in Agriculture
- AI-Assisted Crop Health Assessment

---

## Future Improvements

- Vision Transformer (ViT) implementation
- Real-time disease detection
- Mobile deployment
- Edge AI optimization
- Disease localization using object detection

---

## Author

**MBKM-BRIN Research Program**

Research Area:
Artificial Intelligence • Computer Vision • Deep Learning • Smart Agriculture
