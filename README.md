# 🧠 Fashion MNIST Image Classification with CNN

A deep learning project where I built a Convolutional Neural Network (CNN) using PyTorch to classify clothing items in the Fashion MNIST dataset. This project not only focuses on model accuracy but also incorporates a data analyst's perspective through exploratory data analysis, interpretability, and detailed evaluation.

---

## 📸 Screenshot


![Screenshot 2025-07-06 170632](https://github.com/user-attachments/assets/50720ea4-8b66-4251-a90b-75f2e923ceec)
![Screenshot 2025-07-06 170514](https://github.com/user-attachments/assets/8cbcb4b6-e875-480e-9724-5d1fd6bb8172)

---

## 📚 Project Overview

Fashion MNIST is a dataset of 70,000 grayscale images across 10 fashion categories like T-shirts, sneakers, coats, and more. This project demonstrates how to build, train, and evaluate a CNN model on image data while treating the process with the investigative mindset of a data analyst.

---

## 🚀 Features

- Built a custom CNN using PyTorch
- Achieved ~90% accuracy on test set
- Performed EDA using Matplotlib, Seaborn
- Generated classification report & confusion matrix
- Visualized misclassified images
- Interpreted CNN with feature map visualizations

---

## 🛠️ Tech Stack

- **Languages**: Python
- **Libraries**: PyTorch, NumPy, Pandas, Matplotlib, Seaborn, scikit-learn
- **Tools**: Jupyter Notebook, GitHub

---

## 🧪 Model Architecture

```text
Input: 28x28 grayscale image
→ Conv2D(1→32) + ReLU + MaxPool
→ Conv2D(32→64) + ReLU + MaxPool
→ Flatten
→ Fully Connected (128)
→ Output Layer (10 classes)
