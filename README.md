# Kaggle Deep Learning Course - Notes & Exercises

This repository contains my notes, notebooks, and practice implementations from the **Kaggle Intro to Deep Learning** course. The course covers neural network fundamentals, model training, and deep learning best practices using TensorFlow/Keras.

## 📜 Certificate

![Deep Learning Certificate](Jeewantha%20Sadaruwan%20-%20Intro%20to%20Deep%20Learning.png)

## 🎓 What I Learned

### 1. Linear Models & Neural Network Basics
- Understanding input shapes and model architecture
- Working with tensors and weights
- Training linear regression models
- Data normalization and preprocessing
- Train/validation/test split strategies

### 2. Deep Neural Networks
- Building multi-layer sequential models
- Dense (fully-connected) layers
- Activation functions (ReLU, Sigmoid, Tanh)
- Understanding how activation functions transform data
- Model compilation with optimizers and loss functions

### 3. Training Optimization
- Early stopping callbacks to prevent overfitting
- Configuring `min_delta` and `patience` parameters
- Monitoring training and validation metrics
- Loss visualization and performance tracking
- Batch training and epochs

### 4. Binary Classification
- Building classification models for categorical outcomes
- Using sigmoid activation for binary outputs
- Binary crossentropy loss function
- Accuracy metrics for classification tasks
- Making predictions with probability outputs

### 5. Regularization Techniques
- Dropout layers and how they work
- Understanding random neuron dropping per batch
- Preventing overfitting and co-adaptation
- Balancing model complexity and generalization

## 📁 Project Structure

```
kaggle-deep-learning-notes/
├── dataset/
│   └── wine_quality.csv          # Wine quality dataset for regression
├── exercises/
│   ├── exercise1.ipynb           # Linear models and regression
│   ├── exercise2.ipynb           # Deep networks and activations
│   ├── exercise3.ipynb           # Training optimization
│   └── exercise4.ipynb           # Binary classification
├── note1.ipynb                   # Course notes and concepts
├── main.py                       # Helper scripts
└── README.md                     # This file
```

## 🛠️ Technologies Used

- **TensorFlow/Keras** - Deep learning framework
- **scikit-learn** - Data splitting and preprocessing
- **pandas** - Data manipulation and analysis
- **NumPy** - Numerical computations
- **matplotlib** - Data visualization

## 🚀 Running the Notebooks

1. Clone the repository:
```bash
git clone <repository-url>
cd kaggle-deep-learning-notes
```

2. Install dependencies:
```bash
uv sync
```

3. Activate virtual environment:
```bash
.venv\Scripts\Activate.ps1  # Windows PowerShell
```

4. Open notebooks in VS Code or Jupyter

## 📊 Key Concepts Implemented

- **Regression**: Wine quality prediction using physiochemical measurements
- **Classification**: Student pass/fail prediction from academic features
- **Model Evaluation**: Loss curves, accuracy metrics, train/val/test splits
- **Visualization**: Activation functions, training history, model performance

## 📝 Notes

All exercises include detailed comments and markdown explanations. The notebooks demonstrate practical implementation of deep learning concepts with real-world datasets.
