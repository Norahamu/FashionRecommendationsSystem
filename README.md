# **Fashion Recommendation Project**

## **Team Members**
- **Norah Almubarak**
- **Lama Almazyad**
- **Bayader Aljondeby**
- **Yara Aljasir**
- **Liana Almashharawi**

---

## **Motivation**
The fashion industry is a rapidly growing sector where **visual representation** of products plays a crucial role in consumer decision-making. 

We chose this dataset because:
- The fashion industry **heavily relies on AI-driven solutions** like **image classification and recommendation systems**.
- This dataset provides a **diverse set of fashion product images with metadata**, making it **ideal for machine learning models** for fashion analytics, classification, and visual search.

---

## **Dataset Overview**
The **Fashion Product Images Dataset** consists of **images of fashion products with metadata**, including:
- **Product categories**
- **Gender specifications**
- **Seasonality & Other attributes**

### **Key Features**
✔ **Product Images**: A large collection of fashion product images.  
✔ **Metadata**: Each image is labeled with attributes such as **category, sub-category, gender, season, and usage**.  
✔ **Structured Data**: Includes **CSV files** containing **image paths and metadata**.  
✔ **Potential Use Cases**: **Image classification, recommendation systems, and fashion analytics**.  

---

## **Dataset Source**
The dataset is available on Kaggle:  
🔗 **[Fashion Product Images Dataset](https://www.kaggle.com/datasets/paramaggarwal/fashion-product-images-dataset)**

---

# **Data Analysis & Preprocessing**
The **Jupyter Notebook** in this repository includes the following steps:

### **🔹 Data Preprocessing Pipeline**
**Data Loading & Exploration**  
**Data Visualization** (Category distribution, gender-wise split, etc.)  
**Missing Value Analysis & Handling**  
**Image Resizing & Normalization**  

---

# **Supervised Learning: Fashion Product Classification & Recommendations**
## **Goal**
We trained **supervised learning models** to **classify and recommend fashion products** based on **image features**.

## **Steps in Supervised Learning**
### **Step 1: Feature Extraction using CNN (ResNet50)**
- **Used ResNet50 (Pre-trained CNN Model)** to **extract deep image features**.
- Converted each image into a **feature vector**.

### **Step 2: Training Machine Learning Models**
We trained **two different supervised models**:
1. **Support Vector Machine (SVM)**
2. **Multi-layer Perceptron (MLP) Neural Network**

### **Step 3: Model Comparison**
- Evaluated models using **Accuracy, Precision, Recall, and F1-score**.
- **SVM achieved high accuracy** in fashion classification.

### **Step 4: Recommendation System**
- Used **Cosine Similarity** to recommend similar fashion products.
- Recommendations were based on:
  - **Brand Name**
  - **Age Group**
  - **Gender**
  - **Base Color**
  - **Season**






