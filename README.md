# 🌿 Leaf Disease Detection and Segmentation

A deep learning-based computer vision project that detects and segments diseased regions in crop leaves using image segmentation techniques. This project leverages PyTorch and TorchVision to identify disease-affected areas at the pixel level, helping support early diagnosis and precision agriculture.

---

## 📌 Overview

Plant diseases can significantly reduce crop yield and quality. Manual disease identification is often time-consuming and requires expert knowledge. This project automates the process by using deep learning and image segmentation techniques to detect and highlight infected regions in leaf images.

The model is trained on a publicly available crop disease segmentation dataset and produces segmentation masks that localize diseased areas on plant leaves.

---

## 🚀 Features

* Disease region segmentation from leaf images
* Image preprocessing and augmentation
* Deep learning-based model training
* Pixel-level disease localization
* Visualization of predicted masks
* Model performance evaluation

---

## 🛠️ Technologies Used

* Python
* PyTorch
* TorchVision
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* Pillow (PIL)
* Jupyter Notebook

---

## 📂 Project Structure

```text
Leaf-Disease-Detection-and-Segmentation/
│
├── Leaf Disease Detection and Segmentation.ipynb
├── README.md
├── requirements.txt
├── dataset/
├── outputs/
└── sample_results/
```

---

## 📊 Dataset

This project uses the **Crop Disease Segmentation Dataset** from Roboflow Universe.

**Dataset Source:**

https://universe.roboflow.com/shoaib-hossain-ut2m8/crop-disease-segmentation

### Dataset Features

* Crop leaf images
* Disease segmentation masks
* Pixel-level annotations
* Suitable for semantic segmentation tasks
* Publicly available for research and educational use

---

## 🔍 Workflow

1. Data Collection
2. Data Preprocessing
3. Dataset Preparation
4. Model Training
5. Disease Segmentation
6. Prediction Generation
7. Performance Evaluation
8. Visualization of Results

---

## 📈 Evaluation Metrics

The model performance can be evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Intersection over Union (IoU)
* Dice Coefficient

---

## ▶️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Leaf-Disease-Detection-and-Segmentation.git
cd Leaf-Disease-Detection-and-Segmentation
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
Leaf Disease Detection and Segmentation.ipynb
```

and run all cells.

---

## 📸 Results

The model successfully identifies and segments diseased regions from crop leaf images.

Example outputs include:

* Original Leaf Image
* Ground Truth Mask
* Predicted Disease Mask
* Segmented Disease Region

<img width="1080" height="562" alt="image" src="https://github.com/user-attachments/assets/9eb3f0ae-bd51-41a2-abf6-ba348afa9450" />


---

## 🌱 Applications

* Smart Agriculture
* Crop Health Monitoring
* Precision Farming
* Early Disease Detection
* Agricultural Research

---

## 🔮 Future Improvements

* Real-time disease detection
* Mobile application integration
* Multi-class disease segmentation
* Deployment as a web application
* Improved model architectures and accuracy

---

## 👩‍💻 Author

**Varanasi Mahitha**

B.Tech CSE (AI & ML)

VIT-AP University

---


