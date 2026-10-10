# -Rice-Leaf-Disease-Detection-Using-CNN

# 🌾 Rice Leaf Disease Detection Using CNN

## 📌 About the Project

**Rice Leaf Disease Detection using Convolutional Neural Network (CNN)** is a Deep Learning project designed to classify rice leaf images into disease categories using image processing and neural networks.

The model learns visual features from labeled rice leaf images and predicts the corresponding class for an input image.

This project demonstrates the practical application of Deep Learning and Computer Vision in agriculture.

## 🎯 Project Objectives

- 🌱 Identify rice leaf diseases from images.
- 🧠 Build and train a CNN classification model.
- 🖼️ Learn visual features such as patterns, spots, and discoloration.
- 📊 Evaluate model performance using accuracy and loss.
- 🔍 Predict the class of unseen rice leaf images.
- 🚀 Explore AI-based solutions for smart agriculture.

## 🛠️ Technologies & Libraries

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| TensorFlow | Deep Learning framework |
| Keras | CNN model development |
| NumPy | Numerical computations |
| Matplotlib | Training graphs and visualization |
| Scikit-learn | Model evaluation, if used |
| OpenCV | Image processing, if used |

## 🧠 CNN Model Architecture

The model uses a Convolutional Neural Network to learn spatial features from rice leaf images.

**Typical workflow:**

1. Input image
2. Image resizing and normalization
3. Convolutional layers
4. ReLU activation
5. Max pooling
6. Flatten layer
7. Fully connected Dense layers
8. Softmax output for multiclass classification

*The exact architecture depends on the layers implemented in the training code.*

## ⚙️ How It Works

```text
Rice Leaf Image
       ↓
Image Preprocessing
       ↓
CNN Feature Extraction
       ↓
Classification Layers
       ↓
Softmax Probabilities
       ↓
Predicted Class
```

## 💻 Installation & Setup

### 1. Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
cd Rice-Leaf-Disease-Detection
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

### 3. Activate the environment on Windows

```bash
venv\Scripts\activate
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

## 📦 Requirements

Example dependencies:

```text
tensorflow
numpy
matplotlib
scikit-learn
pillow
```

Install only the packages required by your actual project, and pin compatible versions when necessary.

## ▶️ Running the Project

1. Open the project in VS Code or Jupyter Notebook.
2. Activate your Python environment.
3. Configure the dataset path.
4. Run the training notebook or training script.
5. Evaluate the model on unseen test images.
6. Run the prediction code on a new rice leaf image.

If a trained `.keras` model is already available, you can load it for prediction without retraining, provided the model and preprocessing configuration are compatible.

## 📊 Model Performance

| Metric | Result |
|---|---|
| Training Accuracy | 66.09% |
| Validation Accuracy | 66.27% |
| Validation Loss | 0.8626 |

Model performance should be measured on data that was not used for training. Actual results will depend on the dataset, preprocessing, model architecture, and training configuration.

## 🔬 Key Learning Outcomes

- Understanding CNN architecture.
- Image preprocessing and normalization.
- Training a Deep Learning model.
- Multiclass image classification.
- Model evaluation using accuracy and loss.
- Making predictions on new images.
- Organizing an AI/ML project for GitHub.

## 👨‍💻 Author

**Dheeraj Chouhan**

- GitHub: [@dheeraj24-coder](https://github.com/dheeraj24-coder)

## ⭐ Support

If you find this project useful for learning Deep Learning and Computer Vision, consider giving the repository a star!

---

*Built as a learning project in Deep Learning and AI for Agriculture.*
