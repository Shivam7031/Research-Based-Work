# 📊 CNN Research Work  
### A Comparative Study of Lightweight and Deep Convolutional Architectures for Image Recognition

---

## 📖 Overview

This repository presents a structured research study on Convolutional Neural Networks (CNNs) for image classification.  

The project performs:
- Baseline CNN implementation
- Deep CNN (VGG-style) architecture
- Accuracy comparison across models
- Parameter-efficiency analysis
- Inference time benchmarking
- Hybrid / Neuro-Symbolic extensions (if applicable)

The research is conducted using freely available datasets and open-source tools under non-funded constraints (Google Colab environment).

---

## 🎯 Research Objectives

- Analyze architectural depth vs accuracy trade-offs  
- Compare lightweight vs deep CNN performance  
- Study parameter efficiency and inference latency  
- Evaluate generalization on CIFAR datasets  
- Propose accuracy improvements under computational constraints  

---

## 🧠 Models Implemented

| Model | Type | Parameters | Purpose |
|-------|------|------------|----------|
| Baseline CNN | Shallow CNN | Low | Performance benchmark |
| Deep CNN | VGG-style | Medium | Improved feature extraction |
| Efficient Models | Lightweight CNN | Optimized | Parameter efficiency |
| Hybrid Model | Neuro-Symbolic | Extended | Logical reasoning integration |

Saved Models:
- `baseline_cnn_final`
- `deep_cnn_final`

---

## 📂 Dataset Used

- CIFAR-10  
- CIFAR-100 (optional extension)  
- Future scope: Tiny-ImageNet

---

## ⚙️ Experimental Setup

- Framework: PyTorch  
- Environment: Google Colab  
- Optimizer: Adam  
- Loss Function: CrossEntropyLoss  
- Epochs: 30  
- Batch Size: 64  

Evaluation Metrics:
- Test Accuracy
- Loss Curves
- Parameter Count
- Inference Time (seconds)

---

## 📈 Results Summary

| Model | Test Accuracy | Parameters | Inference Time |
|--------|--------------|------------|----------------|
| Baseline CNN | 0.61 | 110K | 0.000279s |
| Neuro-Symbolic | 0.88 | 110K | 0.000118s |

*(Values represent experimental outputs and may vary with hyperparameter tuning.)*

---

## 🧪 Research Contributions

- Structured comparison of CNN depth impact  
- Efficient architecture design under resource constraints  
- Hybrid reasoning enhancement for accuracy boost  
- Practical benchmarking methodology for academic use  

---

## 🚀 Future Improvements

- Integrate Tiny-ImageNet for higher-resolution evaluation  
- Compare with MobileNetV2 & EfficientNet-B0  
- Add Vision Transformer comparison  
- Apply advanced data augmentation  
- Hyperparameter optimization study  

---

## 📊 Reproducibility

To run the project:

```bash
git clone <repository-url>
cd cnn-research
pip install -r requirements.txt
python train.py
