# Credit Card Fraud Detection using Neural Networks from Scratch

<div align="center">


**A modern, AI-powered Jupyter-based tool that detects fraudulent credit card transactions using a neural network built from scratch**

</div>

---

### Problem
Credit card fraud is a major financial threat, with billions lost annually. Traditional methods struggle with imbalanced data (fraud <0.2% of transactions), leading to missed detections and false alarms.

### Solution
This project builds a neural network from scratch to classify transactions as normal or fraud, using feature scaling, SMOTE balancing, and mini-batch gradient descent for accurate, interpretable predictions.

### Idea
Leverage neural networks to analyze transaction features (Amount, V2, V3, V4) and deliver real-time fraud probability, empowering users to monitor and prevent losses effectively.

### Layout
```
creditcard_nn_from_scratch/
├── creditcard.csv                          # Dataset (Kaggle)
├── creditcard_nn_from_scratch.ipynb        # Main Jupyter Notebook
├── model_weights.npz                       # Trained NN weights (W1, W2)
├── scaler.pkl                              # StandardScaler for features
├── README.md                               # This file
└── images/                                 # Generated plots
    ├── class_distribution_original.png     # Original imbalanced distribution
    ├── class_distribution_resampled.png    # Balanced after SMOTE
    ├── feature_correlation.png             # Feature correlation heatmap
    ├── training_cost.png                   # Cost curve over epochs
    └── confusion_matrix.png                # Evaluation matrix
```


## How to Run the Project on Your Local Machine

### Table of Contents
- Getting Started  
- Prerequisites  
- Installation  
- Usage  

---

## Getting Started
These steps help you set up and run the **Credit Card Fraud Detection using Neural Networks from Scratch** project on your device.

---

## Prerequisites
You need:

- Python 3.8 or newer  
- pip  
- Jupyter Notebook  

Required Python libraries:

- numpy  
- pandas  
- matplotlib  
- seaborn  
- scikit-learn  
- imbalanced-learn  

You can install them using the commands below.

---

## Installation

### 1. Download the Dataset
Get **creditcard.csv** from Kaggle and place it in the project folder.

### 2. Clone the repository
```bash
git clone https://github.com/Basmala-ElKady/Credit-Card-Fraud-Detection-using-Neural-Networks-.git
```

### 3. Navigate to the project directory
```bash
cd "Credit-Card-Fraud-Detection-using-Neural-Networks-"
```

### 4. Create and activate a virtual environment
```bash
python -m venv venv
```

Windows:
```bash
.\venv\Scripts\activate
```

Linux/Mac:
```bash
source venv/bin/activate
```

### 5. Install project dependencies
```bash
pip install numpy pandas matplotlib seaborn scikit-learn imbalanced-learn jupyter
```

---

## Usage

### 1. Run Jupyter Notebook
```bash
jupyter notebook
```

### 2. Open the notebook:
`creditcard_nn_from_scratch.ipynb`

### 3. Run all cells sequentially  
Use **Shift+Enter**.

### Output Files Generated
- `model_weights.npz`  
- `scaler.pkl`  
- Plots saved inside the **images/** folder  

### Test Prediction
After running Cell 8, load the saved model and test new data (see Cell 9).

---

## ⚠️ Disclaimer
This project is for educational purposes only.  
Do not use it in real financial environments without full validation and expert review.

---

## Support
- **GitHub**: [Basmala-ElKady](https://github.com/Basmala-ElKady)

---

<div align="center">

**Made with ❤️ for secure transactions**

[⬆ Back to Top](#how-to-run-the-project-on-your-local-machine)

</div>
