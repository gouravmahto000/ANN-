# ANN-Multi_class Classification
# 🌱 Artificial Neural Network (ANN) for Multi-Class Classification

## 📌 Project Overview

This project demonstrates how to build an **Artificial Neural Network (ANN)** using **TensorFlow/Keras** to classify different varieties of dry beans. The problem is a **multi-class classification** task where the model predicts the bean type based on its physical characteristics.

The project covers the complete machine learning workflow, including data preprocessing, feature scaling, label encoding, one-hot encoding, ANN model building, training, evaluation, and model saving.

---

# 🎯 Objective

The objective of this project is to develop a deep learning model capable of accurately classifying seven different types of dry beans using their geometric and shape-related features.

---

# 📂 Dataset

**Dataset Name:** Dry Bean Dataset

**Source:**
- UCI Machine Learning Repository
- Kaggle

### Dataset Information

- Total Records: **13,611**
- Features: **16 Numerical Features**
- Target Classes: **7**
- Missing Values: **No**
- Problem Type: **Multi-Class Classification**

---

# 🫘 Bean Classes

1. BARBUNYA
2. BOMBAY
3. CALI
4. DERMASON
5. HOROZ
6. SEKER
7. SIRA

---

# 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow
- Keras

---

# 📁 Project Structure

```
ANN-DryBean-Classification/
│
├── Dry_Bean_Dataset.xlsx
├── ANN_Multiclass.ipynb
├── drybean_ann.keras
├── README.md
└── requirements.txt
```

---

# 📊 Machine Learning Workflow

```
Load Dataset
      │
      ▼
Data Exploration
      │
      ▼
Data Preprocessing
      │
      ▼
Label Encoding
      │
      ▼
One-Hot Encoding
      │
      ▼
Train-Test Split
      │
      ▼
Feature Scaling
      │
      ▼
Build ANN Model
      │
      ▼
Compile Model
      │
      ▼
Train Model
      │
      ▼
Model Evaluation
      │
      ▼
Prediction
      │
      ▼
Save Model
```

---

# ⚙ Data Preprocessing

The following preprocessing steps were performed:

- Checked missing values
- Explored dataset structure
- Separated features and target
- Applied Label Encoding
- Applied One-Hot Encoding
- Split dataset into training and testing sets
- Standardized numerical features using StandardScaler

---

# 🧠 ANN Architecture

```
Input Layer
16 Neurons

        │

Hidden Layer
64 Neurons
ReLU

        │

Hidden Layer
32 Neurons
ReLU

        │

Output Layer
7 Neurons
Softmax
```

---

# ⚙ Model Configuration

| Parameter | Value |
|-----------|--------|
| Optimizer | Adam |
| Loss Function | Categorical Crossentropy |
| Activation (Hidden) | ReLU |
| Activation (Output) | Softmax |
| Epochs | 50 |
| Batch Size | 32 |
| Validation Split | 20% |

---

# 📈 Evaluation Metrics

The model was evaluated using:

- Accuracy
- Confusion Matrix
- Classification Report
- Validation Accuracy
- Training Loss
- Validation Loss

---

# 📊 Visualizations

The project includes:

- Accuracy Curve
- Loss Curve
- Confusion Matrix Heatmap

---

# 🚀 Model Saving

The trained model is saved using:

```python
model.save("drybean_ann.keras")
```

---

# 📦 Required Libraries

```bash
pip install tensorflow
pip install pandas
pip install numpy
pip install matplotlib
pip install seaborn
pip install scikit-learn
pip install openpyxl
```

Or install all dependencies at once:

```bash
pip install -r requirements.txt
```

---

# ▶ How to Run

1. Clone the repository.

```bash
git clone <repository-url>
```

2. Navigate to the project folder.

```bash
cd ANN-DryBean-Classification
```

3. Install dependencies.

```bash
pip install -r requirements.txt
```

4. Run the Jupyter Notebook.

```bash
jupyter notebook
```

5. Execute all notebook cells.

---

# 📚 Key Concepts Covered

- Artificial Neural Networks (ANN)
- Multi-Class Classification
- Data Preprocessing
- Feature Scaling
- Label Encoding
- One-Hot Encoding
- TensorFlow/Keras
- ReLU Activation
- Softmax Activation
- Categorical Crossentropy
- Model Evaluation
- Deep Learning Workflow

---

# 💡 Future Improvements

- Add Dropout layers to reduce overfitting.
- Apply Early Stopping.
- Perform Hyperparameter Tuning.
- Experiment with deeper neural networks.
- Deploy the trained model as a web application.

---

# 📄 License

This project is created for educational and learning purposes.

---

# 👨‍💻 Author

**Gourav Kumar**

Aspiring Data Scientist | Machine Learning Enthusiast | Python Developer

**Skills:** Python, SQL, Machine Learning, Deep Learning, TensorFlow, Keras, Pandas, NumPy, Scikit-learn, Power BI, Git & GitHub

---

⭐ If you found this project useful, consider giving it a star on GitHub!
