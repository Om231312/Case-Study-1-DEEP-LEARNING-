# 🧠 MNIST Handwritten Digit Classification

<p align="center">
A Deep Learning project that classifies handwritten digits (0–9) using the MNIST dataset.
</p>

---

## 📌 Project Overview

```
This project implements a Neural Network model to classify handwritten digits
using the MNIST dataset. The model learns patterns from grayscale images
of digits and predicts the correct number from 0–9.
```

The MNIST dataset is one of the most popular datasets used for learning **Machine Learning and Deep Learning concepts**.

---

## 📂 Dataset Information

```
Dataset Name : MNIST
Total Images : 70,000
Training Data : 60,000
Testing Data : 10,000
Image Size : 28 × 28 pixels
Color Type : Grayscale
Total Features : 784 pixels per image
```

Each image represents a handwritten digit between **0 and 9**.

---

## ⚙️ Technologies Used

```
✔ Python
✔ NumPy
✔ Scikit-learn
✔ TensorFlow / Keras
✔ Matplotlib
```

---

## 🧠 Model Architecture

```
Input Layer
   ↓
784 Neurons (28×28 pixels)

Hidden Layers
   ↓
Dense Layers with Activation Functions

Output Layer
   ↓
10 Neurons (Digits 0–9)
Activation Function : Softmax
```

---

## 🔄 Project Workflow

```
1️⃣ Load MNIST Dataset
2️⃣ Normalize pixel values (0–255 → 0–1)
3️⃣ Convert labels using OneHotEncoder
4️⃣ Split data into training and validation sets
5️⃣ Build Neural Network model
6️⃣ Train the model using epochs
7️⃣ Evaluate model accuracy
8️⃣ Predict handwritten digits
```

---

## 🧪 Model Training

Example training code:

```python
history = model.fit(
    train_generator,
    epochs=10,
    validation_data=val_generator
)
```

### 📖 What is an Epoch?

```
Epoch = One complete pass of the entire training dataset
through the neural network.
```

Example:

```
Epoch 1 → Model sees all images once
Epoch 2 → Model sees them again and improves learning
Epoch 10 → Model becomes more accurate
```

---

## 📊 Model Performance

```
Training Accuracy  : ~98%
Validation Accuracy : ~97%
```

The model performs very well in recognizing handwritten digits.

---

## 📁 Project Structure

```
MNIST-Digit-Classifier
│
├── mnist.ipynb
└── README.md
```

---

## 🚀 How to Run the Project

### 1️⃣ Clone the Repository

```
git clone https://github.com/yourusername/mnist-digit-classifier.git
```

### 2️⃣ Install Dependencies

```
pip install numpy scikit-learn tensorflow matplotlib
```

### 3️⃣ Run the Project

```
python mnist_model.py
```

---

## 🎯 Applications

```
✔ Handwritten digit recognition
✔ Bank cheque processing
✔ Postal code recognition
✔ Optical Character Recognition (OCR)
✔ Document automation
```

---

## 👨‍💻 Author

```
Name : Om Prakash Kannaujiya
GitHub : https://github.com/yourusername
```

---

⭐ If you like this project, consider giving it a **star ⭐ on GitHub!**
