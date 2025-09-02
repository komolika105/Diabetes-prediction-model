# 🩺 Diabetes Prediction Model

A machine learning project to predict diabetes using patient health data.  
Implemented in **Python** with multiple models and accuracy comparison.

## 🔹 Features
- Data preprocessing with StandardScaler
- Models: KNN, Decision Tree, MLP Classifier
- Accuracy evaluation & comparison
- Visualization of results

## 🛠️ Tech Stack
- Python 3
- Scikit-learn
- Matplotlib
- NumPy, Pandas

## ⚙️ Usage
1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
2. Run the notebook:
   ```bash
   jupyter notebook diabetes_prediction.ipynb
   ```

## 📊 Results
| Model                 | Test Accuracy |
|------------------------|--------------:|
| KNN (n=9)             | ~78% |
| Decision Tree (depth=3)| ~74% |
| MLP (tuned)           | ~80% |

✅ Best model: **Tuned MLP Classifier** (~80% accuracy).
