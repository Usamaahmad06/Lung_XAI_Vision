# VisualIntelligence-XAI

This project compares the performance of a 2D Convolutional Neural Network (CNN) and a Scattering Network (ScatNet) for binary classification of lung cancer histopathological images. It also implements and evaluates an Explainable AI (XAI) method to generate attribution maps for both models.

## 🎯 Objectives

- Train a CNN and ScatNet on lung cancer histopathology images (adenocarcinoma vs benign).
- Perform k-fold cross-validation to assess generalization.
- Compare filters extracted from both models.
- Implement an XAI method from scratch.
- Use Captum library to validate attribution maps.
- Analyze and interpret the explainability results.

## 📁 Dataset

- **Source**: [Kaggle Dataset](https://www.kaggle.com/datasets/rm1000/lung-cancer-histopathological-images)
- **Original Paper**: [arXiv:1912.12142v1](https://arxiv.org/abs/1912.12142v1)
- **Classes Used**: Adenocarcinoma vs Benign (binary classification)

## 🛠️ Technologies

- Python, PyTorch, TorchVision
- OpenCV, PIL, NumPy, Matplotlib
- Scikit-learn, TQDM, Seaborn
- Captum (for XAI comparison)

## 📊 Methodology

1. Dataset preprocessing and splitting
2. Implementation of:
   - CNN with fully connected classifier
   - ScatNet with same classifier structure
3. K-Fold cross-validation on both models
4. Evaluation: Accuracy and F1 Score
5. Filter extraction and comparison
6. Custom implementation of XAI method
7. Attribution maps with custom XAI and Captum
8. Visual and analytical comparison

## 📈 Results

- CNN and ScatNet performance compared using mean Accuracy & F1 Score.
- Filter visualization for both models.
- Attribution maps validated via Captum.
- Insightful comparison of interpretability and model behavior.

## ▶️ How to Run

1. Clone the repo
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
