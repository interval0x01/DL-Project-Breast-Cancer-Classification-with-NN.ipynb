# 🧠 Breast Cancer Classification with Neural Networks

A deep learning project that classifies breast cancer tumors as **Malignant** or **Benign** using a Neural Network built with **TensorFlow/Keras**.

---

## 📌 Project Overview

This project demonstrates how to build, train, and evaluate a simple Artificial Neural Network (ANN) for binary classification using the Breast Cancer Wisconsin dataset.

The workflow includes:

* Loading the dataset
* Data preprocessing
* Feature scaling
* Train/Test split
* Building a Neural Network
* Training the model
* Evaluating performance
* Making predictions

---

## 📂 Project Structure

```
.
├── DL Project 1. Breast Cancer Classification with NN.ipynb
├── requirements.txt
├── README.md
└── .gitignore
```

---

## 📊 Dataset

The project uses the **Breast Cancer Wisconsin Diagnostic Dataset** provided by **scikit-learn**.

Dataset information:

* Samples: **569**
* Features: **30**
* Classes:

  * 0 → Malignant
  * 1 → Benign

---

## 🛠 Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Pandas
* Matplotlib
* Scikit-learn

---

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/your-repository.git
cd your-repository
```

Install the required packages:

```bash
pip install -r requirements.txt
```

---

## ▶️ Running the Project

Open the notebook:

```bash
jupyter notebook
```

or

```bash
jupyter lab
```

Then run all cells inside:

```
DL Project 1. Breast Cancer Classification with NN.ipynb
```

---

## 🧠 Neural Network Architecture

The model is built using TensorFlow/Keras with:

* Input Layer (30 features)
* Hidden Dense Layers
* ReLU activation
* Output Layer
* Sigmoid activation (Binary Classification)

Loss Function:

```
Binary Crossentropy
```

Optimizer:

```
Adam
```

Evaluation Metric:

```
Accuracy
```

---

## 📈 Results

The trained model is evaluated on the test dataset using accuracy.

Example output:

```
Test Accuracy: ~97%
```

*(Actual accuracy may vary due to random initialization.)*

---

## 📚 Requirements

```
tensorflow
numpy
pandas
matplotlib
scikit-learn
```

Install them using:

```bash
pip install -r requirements.txt
```

---

## 🚀 Future Improvements

* Hyperparameter tuning
* Early Stopping
* Dropout Regularization
* Model Checkpointing
* Confusion Matrix
* ROC Curve
* Precision, Recall, and F1 Score

---

## 👨‍💻 Author

**Omar Emad**

Deep Learning & AI Enthusiast

---

## ⭐ License

This project is available for educational purposes.
