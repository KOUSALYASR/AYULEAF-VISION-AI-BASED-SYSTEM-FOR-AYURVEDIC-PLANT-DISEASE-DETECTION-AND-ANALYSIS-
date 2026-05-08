# AYULEAF VISION: AI-Based System for Ayurvedic Plant Disease Detection and Analysis

## Overview
AYULEAF VISION is an AI-powered intelligent diagnostic system developed for disease detection and analysis of Ayurvedic medicinal plants using deep learning and computer vision techniques. The system integrates disease classification, lesion segmentation, explainable AI, severity estimation, environmental analysis, and automated report generation into a unified diagnostic pipeline.

The project focuses on four major Ayurvedic medicinal plants:
- Neem
- Tulsi
- Turmeric
- Aloe Vera

The proposed system is designed to support farmers, herbal practitioners, and agricultural researchers through accurate, scalable, and interpretable plant disease diagnosis.

---

## Problem Statement
Traditional diagnosis of Ayurvedic plant diseases relies heavily on manual visual inspection, which is time-consuming, inconsistent, and difficult to scale. Existing AI-based plant disease detection systems mainly focus on commercial crops and lack:
- Ayurvedic plant-specific disease analysis
- Explainable prediction mechanisms
- Disease severity estimation
- Environmental condition analysis

This project addresses these limitations through an integrated AI-driven diagnostic framework.

---

## Objectives
- Develop a deep learning-based system for Ayurvedic plant disease classification
- Improve disease visibility using CLAHE-based image enhancement
- Perform HSV-based lesion segmentation for disease severity estimation
- Integrate Grad-CAM explainability for interpretable AI predictions
- Analyze environmental conditions affecting plant health
- Generate automated diagnostic reports with treatment recommendations

---

## Dataset
- 13,460 leaf images
- 18 disease and healthy classification categories
- 4 Ayurvedic medicinal plant species

Dataset split:
- 70% Training
- 20% Validation
- 10% Testing

---

## Methodology

### Data Preparation
- Dataset flattening and restructuring
- Stratified dataset splitting
- Data augmentation and normalization

### Image Enhancement
- CLAHE enhancement in LAB colour space
- Contrast optimization for improved lesion visibility
- HSV-based preprocessing techniques

### Model Development
- Transfer learning using MobileNetV2
- TensorFlow/Keras-based deep learning implementation
- GPU-accelerated training using Google Colab

### Lesion Segmentation
- HSV-based disease region segmentation
- Morphological operations for segmentation refinement
- Severity estimation using lesion ratio analysis

### Explainable AI
- Grad-CAM heatmap generation
- Visual interpretation of disease prediction regions

### Environmental Analysis
- Temperature analysis
- Humidity analysis
- Soil moisture interpretation
- Rule-based environmental recommendations

### Report Generation
- Automated diagnostic report generation
- Excel-based report export
- Treatment recommendation workflow

---

## System Architecture
Leaf Image → CLAHE Enhancement → MobileNetV2 Classification → HSV Lesion Segmentation → Grad-CAM Explainability → Environmental Analysis → Diagnostic Report Generation

---

## Results
- Achieved **90.13% test accuracy**
- Achieved **89.87% weighted F1-score**
- Successfully classified 18 disease categories across 4 medicinal plant species
- Improved disease visibility using CLAHE preprocessing techniques
- Generated interpretable Grad-CAM visualizations for prediction transparency
- Enabled disease severity estimation using HSV-based lesion analysis

---

## Performance Metrics
- Accuracy: **90.13%**
- Weighted F1-score: **89.87%**
- Model evaluated using Precision, Recall, and F1-score

---

## Technologies Used
- Python
- TensorFlow / Keras
- MobileNetV2
- OpenCV
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- Google Colab

---

## Key Features
- AI-powered Ayurvedic plant disease detection
- Transfer learning using MobileNetV2
- CLAHE-based image enhancement
- HSV-based lesion segmentation
- Grad-CAM explainability
- Environmental condition analysis
- Automated diagnostic report generation
- Multi-class disease prediction system

---

## Conclusion
AYULEAF VISION demonstrates how deep learning, explainable AI, and computer vision can be integrated into a unified intelligent framework for Ayurvedic plant disease detection and analysis. The system delivers accurate, interpretable, and scalable disease diagnosis suitable for smart agriculture and medicinal plant monitoring applications.

---

## Future Work
- Deploy the system as a scalable cloud-based diagnostic platform
- Extend support for additional medicinal plant species and diseases
- Integrate real-time mobile and IoT-based agricultural monitoring systems
