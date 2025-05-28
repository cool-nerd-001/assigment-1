Name: Poorna Chander Oruganti
700#: 700771980

# 📘 Assignment 1: Tensor Manipulations, Loss Functions & Neural Network Training

## 🔍 Overview

This notebook explores core TensorFlow and machine learning tasks, including:

1. **Tensor Manipulations and Reshaping**  
   Understanding reshaping and broadcasting mechanics in TensorFlow.

2. **Loss Functions and Hyperparameter Tuning**  
   Using `MLPRegressor` and `MLPClassifier` with varied hyperparameters to assess the impact on performance.

3. **Train a Neural Network and Log to TensorBoard**  
   A neural network is trained on standard datasets (Diabetes and Iris). Logging and visualization are optionally supported using TensorBoard when using Keras models.

---

## 🧪 Key Concepts

- **Tensor Reshaping and Broadcasting** with TensorFlow.
- **Loss Metrics**: Mean Squared Error for regression, Log Loss for classification.
- **Neural Network Training**: Multi-layer perceptrons (MLPs) for both tasks.
- **TensorBoard Logging**: (Optional enhancement) Training progress and metrics can be logged and visualized via TensorBoard when using Keras.

---

## 🧠 Neural Network Training

- Models trained:
  - **`MLPRegressor`** on Diabetes dataset.
  - **`MLPClassifier`** on Iris dataset.
- Experiments include varying hidden layer sizes: `(32,)`, `(64,)`, `(128,)`, and `(64, 32)`.
- Training metrics and performance are compared using standard evaluation techniques.

---

## 🛠 Technologies Used

- Python
- TensorFlow
- scikit-learn
- Jupyter Notebook
- *(Optional)* TensorBoard (for Keras-based extensions)

---

## 🚀 Getting Started

1. Install dependencies:
   ```bash
   pip install tensorflow scikit-learn matplotlib
   ```

2. Launch the notebook:
   ```bash
   jupyter notebook Assignment_1.ipynb
   ```

3. *(Optional)* To use TensorBoard with Keras:
   ```bash
   tensorboard --logdir=logs
   ```
