# 📸 Image Blur vs. Sharp Classification Using Traditional Neural Networks (MLP)

A smart, high-efficiency solution for classifying images into **Blurred** or **Sharp**. This project leverages handcrafted feature engineering combined with a traditional Multi-Layer Perceptron (MLP) network instead of computationally expensive Convolutional Neural Networks (CNNs), making it an ideal choice for resource-constrained environments.

---

## 📂 Project Assets & Documentation

All project documentation, analysis, and presentation materials are fully integrated. You can access them directly via the links below:

* 📄 **[View Full Project Documentation (PDF)](./Project%20documentation%20DIP.pdf)**
* 📊 **[Download Project Presentation (PowerPoint)](./PI%20project%20%281%29.pptx)**
* 🗂️ **[Download Demo Files (Zip)](./demo.zip)**


---

## 🛠️ Technical Overview & Tech Stack

* **Programming Language:** Python 🐍
* **Development Environment:** Jupyter Notebook (`Copy_of_version_2_of_DIP.ipynb`)
* **Model Architecture:** Multi-Layer Perceptron (MLP) Neural Network
* **Dataset Size:** Trained and evaluated on **11,175 images**.
* **Computational Approach:** Instead of using deep layers (like CNNs) to automatically learn features, this approach utilizes **44 handcrafted features** rooted in Digital Image Processing (DIP) domain knowledge (such as edge sharpness, contrast, and blur metrics) to feed the network, drastically reducing training time and computational overhead.

---

## 🚀 Project Pipeline

1. **Image Preprocessing & Feature Extraction:** Digital analysis of images to extract 44 statistical and structural blur/sharp metrics.
2. **Model Design:** Designing and configuring a traditional MLP network tailored to the shape of the extracted features.
3. **Training & Regularization:** Training the network while implementing strategies to prevent overfitting, ensuring robust generalization.

---

## 📊 Key Results

* Achieved a solid overall classification accuracy of **78%**.
* Demonstrated exceptionally high precision and sensitivity in **Blur Detection**.
* Successfully eliminated overfitting, ensuring stable performance and reliability on completely unseen test data.

---

## 👤 Developed by:
* **Nada Alaklook**
* 🔗 [Connect with me on LinkedIn](https://linkedin.com/in/nada-alaklook-725049252)
