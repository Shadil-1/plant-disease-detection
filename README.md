# 🌿 Plant Disease Detection Using CNN

An image classification project that uses **Convolutional Neural Networks (CNNs)** to detect and classify plant diseases from plant leaf images.

The goal of this project is to demonstrate how deep learning and computer vision can be used in agriculture to assist with the early identification of plant diseases.

---

## 📌 Project Overview

Plant diseases can significantly affect crop quality and agricultural productivity. Early detection of diseases can help farmers and agricultural professionals take appropriate action.

This project uses a **Convolutional Neural Network (CNN)** to analyze images of plant leaves and classify them based on their disease category.

The model is trained using plant leaf image data and saved as a reusable Keras model.

---

## ✨ Features

* 🌱 Plant leaf image classification
* 🧠 Deep Learning using CNN
* 🖼️ Image preprocessing
* 📊 Model training and evaluation
* 💾 Trained model saved in Keras format
* 📓 Jupyter Notebook implementation

---

## 🏗️ Project Structure

```text
plant-disease-detection/
│
├── data/
│   └── Plant disease dataset
│
├── images/
│   └── Project images and visualizations
│
├── models/
│   └── plant_disease_cnn.keras
│
├── notebooks/
│   ├── Plant Disease Detection and Classification Using CNN.ipynb
│   ├── overview.md
│   └── workflow.md
│
└── README.md
```

---

## 🧠 Model Architecture

The project uses a **Convolutional Neural Network (CNN)** for image classification.

A CNN is particularly suitable for this task because it can automatically learn important visual features from images, such as:

* Leaf shape
* Texture
* Color patterns
* Spots
* Discoloration
* Disease-related visual patterns

### General Workflow

```text
Plant Leaf Image
       │
       ▼
Image Preprocessing
       │
       ▼
CNN Model
       │
       ▼
Feature Extraction
       │
       ▼
Classification
       │
       ▼
Predicted Plant Disease
```

---

## 🛠️ Technologies Used

| Technology                | Purpose                               |
| ------------------------- | ------------------------------------- |
| Python                    | Core programming language             |
| TensorFlow / Keras        | Deep learning framework               |
| CNN                       | Image classification model            |
| Jupyter Notebook          | Model development and experimentation |
| NumPy                     | Numerical computing                   |
| Matplotlib                | Data visualization                    |
| OpenCV / Image Processing | Image preprocessing                   |

---

## 📂 Dataset

The project uses a dataset of plant leaf images stored in the `data/` directory.

The dataset is used to train the CNN model to recognize different plant disease categories based on visual characteristics of the leaves.

Before training, the images are processed and prepared for the deep learning model.

Typical preprocessing steps include:

* Resizing images
* Normalizing pixel values
* Converting images into numerical arrays
* Splitting data into training and testing sets

---

## 🚀 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/Shadil-1/plant-disease-detection.git
```

Move into the project directory:

```bash
cd plant-disease-detection
```

---

### 2. Create a Virtual Environment

```bash
python -m venv venv
```

### Windows

```bash
venv\Scripts\activate
```

### Linux / macOS

```bash
source venv/bin/activate
```

---

### 3. Install Required Libraries

Install the required Python libraries:

```bash
pip install tensorflow numpy matplotlib jupyter
```

Depending on the image-processing code used in the notebook, you may also need:

```bash
pip install opencv-python
```

---

## ▶️ Running the Project

Start Jupyter Notebook:

```bash
jupyter notebook
```

Then open:

```text
notebooks/Plant Disease Detection and Classification Using CNN.ipynb
```

Run the notebook cells sequentially to:

1. Load the dataset
2. Preprocess plant leaf images
3. Build the CNN model
4. Train the model
5. Evaluate model performance
6. Save the trained model

---

## 💾 Trained Model

The trained CNN model is saved in the `models/` directory.

```text
models/
└── plant_disease_cnn.keras
```

The model can be loaded using TensorFlow/Keras:

```python
from tensorflow.keras.models import load_model

model = load_model("models/plant_disease_cnn.keras")
```

---

## 🔄 Project Workflow

```text
Dataset
   │
   ▼
Image Preprocessing
   │
   ▼
Data Preparation
   │
   ▼
CNN Model Development
   │
   ▼
Model Training
   │
   ▼
Model Evaluation
   │
   ▼
Save Trained Model
   │
   ▼
Plant Disease Prediction
```

---

## 📊 Potential Applications

This project can be extended for use in:

* 🌾 Smart agriculture systems
* 📱 Mobile plant disease detection applications
* 🛰️ Agricultural monitoring
* 🤖 AI-powered farming tools
* 🌱 Crop health monitoring systems

---

## 🔮 Future Improvements

Possible future improvements include:

* 📱 Developing a mobile application
* 🌐 Creating a web-based prediction interface
* 📸 Real-time plant disease detection
* 📊 Improving model accuracy through data augmentation
* 🧠 Experimenting with transfer learning models such as EfficientNet or MobileNet
* 🚀 Deploying the trained model as an API
* 🌍 Supporting additional plant species and diseases

---

## 👨‍💻 Author

**Shadil K**

Data Science and AI enthusiast with interests in:

* Machine Learning
* Deep Learning
* Computer Vision
* Artificial Intelligence
* Data Science
* Agricultural AI

---

## ⭐ Support

If you find this project useful, consider giving the repository a ⭐.

---

## 📄 License

This project is intended for educational and research purposes.
