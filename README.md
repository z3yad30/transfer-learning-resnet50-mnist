# transfer-learning-resnet50-mnist

---

## 📘 Transfer Learning with ResNet-50

```markdown
# Transfer Learning with ResNet-50 for Image Classification

## 📌 Project Overview
This project applies transfer learning using the pretrained ResNet-50 architecture to perform image classification. The objective is to leverage a deep, pretrained convolutional network to improve performance and training efficiency on a custom image classification task.

## 🧠 Why Transfer Learning?
Training deep neural networks from scratch is computationally expensive and data-intensive. Transfer learning allows reuse of learned feature representations from large-scale datasets, enabling:
- Faster convergence
- Improved accuracy
- Reduced training time

## 🏗 Model Architecture
- Base Model: **ResNet-50** (pretrained on ImageNet)
- Frozen convolutional base for feature extraction
- Custom fully connected layers added on top
- Fine-tuning applied selectively to improve task-specific performance

## 📂 Data Preprocessing
- Image resizing to match ResNet-50 input requirements
- Normalization and scaling
- Conversion of grayscale images to RGB when required
- Efficient memory handling during training

## ⚙️ Technologies Used
- Python
- TensorFlow / Keras
- Pretrained ResNet-50
- NumPy
- Matplotlib
- Jupyter Notebook

## 📊 Training & Evaluation
- Optimizer: Adam
- Loss Function: Categorical Crossentropy
- Metrics: Accuracy
- Model performance evaluated on validation and test sets

## ✅ Results
The transfer learning approach demonstrates strong performance with significantly reduced training time compared to training from scratch, validating the effectiveness of pretrained deep learning models.

## 🚀 How to Run
1. Clone the repository
2. Install dependencies:
   ```bash
   pip install tensorflow numpy matplotlib
3. Launch Jupyter Notebook:
  ```bash
  jupyter notebook
Execute the notebook cells in order

4. 📌 Key Takeaways

Practical application of transfer learning

Experience working with pretrained deep learning models

Improved model efficiency and performance

Understanding of fine-tuning strategies
