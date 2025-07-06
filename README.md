# 🧠 Fashion MNIST Image Classification with CNN

A deep learning project where I built a Convolutional Neural Network (CNN) using PyTorch to classify clothing items in the Fashion MNIST dataset. This project not only focuses on model accuracy but also incorporates a data analyst's perspective through exploratory data analysis, interpretability, and detailed evaluation.

---

## 📸 Screenshot


![Screenshot 2025-07-06 170632](https://github.com/user-attachments/assets/50720ea4-8b66-4251-a90b-75f2e923ceec)
![Screenshot 2025-07-06 170514](https://github.com/user-attachments/assets/8cbcb4b6-e875-480e-9724-5d1fd6bb8172)

---

# 🧠 Fashion MNIST Image Classification with CNN

A deep learning project where I built a Convolutional Neural Network (CNN) using PyTorch to classify clothing items in the Fashion MNIST dataset. This project integrates image classification, data analysis, and model interpretability — showcasing my technical and analytical skills as a data analyst.

---

## 📸 Screenshot

> *(Example output: misclassified predictions by the CNN)*

![Misclassified Images](assets/misclassified_examples.png)

---

## 📚 Project Overview

Fashion MNIST is a dataset of 70,000 grayscale images categorized into 10 different fashion items (e.g., t-shirts, trousers, sneakers). The goal of this project is to classify these images using a custom-built CNN while performing exploratory data analysis and model evaluation — just like a data analyst would approach a real-world classification problem.

---

## 🚀 Features

- 📊 Exploratory Data Analysis (EDA)
- 🧠 Custom CNN using PyTorch
- 🎯 Achieved ~90% accuracy on the test set
- 📈 Visualized confusion matrix & misclassified predictions
- 🔍 Feature map visualization for interpretability
- 🧪 Classification reports with precision, recall, and F1-scores

---

## 🛠️ Tech Stack

- **Languages**: Python
- **Libraries**: PyTorch, NumPy, Pandas, Seaborn, Matplotlib, scikit-learn
- **Tools**: Jupyter Notebook, GitHub

---

## 🧪 Model Architecture

Input: 28x28 grayscale image
- Conv2D(1→32) + ReLU + MaxPool
- Conv2D(32→64) + ReLU + MaxPool
- Flatten
- Fully Connected (128)
- Output Layer (10 classes)


---

## 📈 Results

- **Test Accuracy**: ~90%
- **Best Performing Classes**: Sandal, Trouser, Sneaker
- **Misclassifications**: Most confusion between Shirt vs T-shirt/Top
- **Evaluation Tools**:
  - Confusion Matrix (10x10)
  - Classification Report (precision, recall, F1-score)
  - Misclassified image visualization

---

## 💡 Future Improvements

- Use **Grad-CAM** for more detailed visual explainability
- Add **Streamlit-based Web App** to interact with predictions
- Introduce **data augmentation** to improve robustness

---

## 📁 Folder Structure

Fashion-CNN/
│
├── notebooks/
│ └── Fashion_MNIST_CNN.ipynb
├── model/
│ └── cnn_model.py
├── assets/
│ └── misclassified_examples.png
├── README.md


---

## 🧑‍💼 About Me

I'm **Somya Agrawal**, a B.Tech student specializing in Data Analytics at MIT ADT University. I enjoy bridging the gap between data and decisions by blending statistical thinking with practical machine learning. My technical toolbox includes SQL, Python, Excel, Power BI, and hands-on model building with scikit-learn and PyTorch.

> 🔗 Reach me:  
> 📧 agrawalsomya12@gmail.com  
> 📱 +91 74896 93183  

---

## 🌟 Give it a Star

If you found this project useful or insightful, feel free to ⭐ star it on GitHub. It helps me stay motivated and grow!

