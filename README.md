# 🌱 Crop Recommendation System using Artificial Neural Network (ANN)

## 📌 Overview

This project implements a **Crop Recommendation System** using an **Artificial Neural Network (ANN)** built with TensorFlow/Keras. The model predicts the most suitable crop based on soil nutrients and environmental conditions, helping support data-driven agricultural decisions.

The project includes data preprocessing, exploratory data analysis (EDA), model training, evaluation, and visualization of training performance.

---

## 🚀 Features

- Data preprocessing using Pandas
- Exploratory Data Analysis (EDA)
- Label Encoding for crop labels
- Train-Test Split
- Deep Neural Network using TensorFlow/Keras
- Multi-class Crop Classification
- Model evaluation on test data
- Training vs Validation Accuracy visualization

---

## 📂 Dataset

The dataset contains the following features:

| Feature | Description |
|---------|-------------|
| Nitrogen (N) | Nitrogen content in soil |
| Phosphorus (P) | Phosphorus content in soil |
| Potassium (K) | Potassium content in soil |
| Temperature | Temperature (°C) |
| Humidity | Relative Humidity (%) |
| pH | Soil pH value |
| Rainfall | Rainfall (mm) |
| Label | Recommended Crop |

---

## 🛠️ Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🧠 Model Architecture

The ANN consists of the following layers:

Input Layer
↓
Dense (128 neurons, ReLU)
↓
Dense (64 neurons, ReLU)
↓
Dense (32 neurons, ReLU)
↓
Dense (16 neurons, ReLU)
↓
Output Layer (Softmax)

### Model Configuration

- Optimizer: Adam
- Loss Function: Sparse Categorical Crossentropy
- Activation Function: ReLU
- Output Activation: Softmax
- Epochs: 50
- Batch Size: 16

---

## 📈 Workflow

1. Load Dataset
2. Check Missing Values
3. Check Duplicate Records
4. Perform Basic Data Analysis
5. Encode Crop Labels
6. Split Dataset into Training and Testing Sets
7. Build ANN Model
8. Train the Model
9. Evaluate Model Performance
10. Visualize Accuracy Curves

---

## 📊 Results

The model was trained for **50 epochs** using the Adam optimizer.

Performance was evaluated using:

- Test Loss
- Test Accuracy
- Training Accuracy Curve
- Validation Accuracy Curve

---

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Crop-Recommendation-ANN.git
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Project

Open the Jupyter Notebook or Google Colab notebook and execute all cells sequentially.

---

## 📁 Project Structure

```
Crop-Recommendation-ANN/
│
├── Crop_Recommendation.ipynb
├── crop.csv
├── requirements.txt
├── README.md
└── images/
```

---

## 📚 Future Improvements

- Hyperparameter tuning
- Model checkpointing
- Deploy using Flask or Streamlit
- Real-time crop recommendation web application
- Compare ANN with Machine Learning models such as Random Forest and XGBoost

---

## 👩‍💻 Author

**Shobha**

B.Tech Computer Science Engineering

---

## ⭐ If you found this project useful, consider giving it a star!
