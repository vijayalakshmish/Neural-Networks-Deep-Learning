# 🧠 Sentiment Analysis using LSTM (RNN)

A deep learning project using TensorFlow/Keras to classify text sentiment (positive or negative) with a custom-built LSTM-based RNN model. It includes preprocessing, training, evaluation, and explainability using SHAP.

---

## 🚀 Features

- Built synthetic dataset for binary sentiment classification  
- Used LSTM layers for sequential modeling  
- Evaluated performance with accuracy & confusion matrix  
- Visualized results using Seaborn  
- Used SHAP for model explainability  
- Supports real-time sentiment predictions

---

## 🛠️ Tech Stack

- Python 3.11  
- TensorFlow 2.18  
- Keras  
- NumPy, Pandas  
- Scikit-learn  
- Matplotlib, Seaborn  
- SHAP (Explainable AI)

---

## 🗃️ Dataset

A small, handcrafted dataset of 24 sentences:
- 12 Positive samples (`label = 1`)
- 12 Negative samples (`label = 0`)

---

## 📐 Model Architecture

- `Embedding Layer` (vocab size = 100, embedding dim = 16)  
- `LSTM Layer` with 64 units, dropout = 0.3  
- `Dense Layer` with 32 units + ReLU  
- `Dropout Layer`  
- `Output Layer` with sigmoid activation

---

## 📈 Training

- Loss Function: `binary_crossentropy`  
- Optimizer: `adam`  
- Epochs: 10  
- Batch Size: 2  
- Train/Test Split: 80/20

---

## 📊 Evaluation

- Accuracy on test set: **~40%**  
- Confusion Matrix plotted  
- Sentiment prediction function available  
- SHAP visualizations added

---

## 💬 Prediction Example

```python
predict_sentiment("I hate this product")
# Output: Sentiment: negative
