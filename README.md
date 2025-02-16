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
**Product Images**: A large collection of fashion product images.  
**Metadata**: Each image is labeled with attributes such as **category, sub-category, gender, season, and usage**.  
**Structured Data**: Includes **CSV files** containing **image paths and metadata**.  
**Potential Use Cases**: **Image classification, recommendation systems, and fashion analytics**.  

---

## **Dataset Source**
The dataset is available on Kaggle:  
**[Fashion Product Images Dataset](https://www.kaggle.com/datasets/paramaggarwal/fashion-product-images-dataset)**

---

# **Data Analysis & Preprocessing**
The **Jupyter Notebook** in this repository includes the following steps:

### **Data Preprocessing Pipeline**
**Data Loading & Exploration**  
**Data Visualization** (Category distribution, gender-wise split, etc.)  
**Missing Value Analysis & Handling**  
**Image Resizing & Normalization**  

---

# **Supervised Learning: Fashion Product Classification & Recommendations**
## **Goal**
We trained **supervised learning models** to **classify and recommend fashion products**.

## **Steps in Supervised Learning**

1. **Feature Extraction with ResNet50**
   
   Used ResNet50, a Convolutional Neural Network (CNN) pre-trained on ImageNet.
   
   Extracted deep features from images without modifying ResNet50’s weights.
   
   Flattened the extracted feature vectors for classifier input.
   
   Note: ResNet50 model was trained with supervised learning on ImageNet.

2. **Model Selection**
   
   Selected Support Vector Machine (SVM) and MLP (Neural Network) as classifiers.
   
   These models require labeled data to learn decision boundaries.

3. **Model Training**
   
   Trained both SVM and MLP using labeled extracted features.
   
   Optimized hyperparameters to improve classification accuracy.

4. **Model Evaluation**
   
   Evaluated classification performance on the test dataset (with known labels).
   
   Metrics used:
   
   - Accuracy
   - Precision, Recall, F1-score
   - Confusion Matrix Analysis

5. **Fashion Product Recommendation**
   
   Used classification results to recommend similar products.
   
   Analyzed feature embeddings to suggest visually similar items from the same predicted category.

## **Model Performance Comparison**

1. **Support Vector Machine (SVM)**
   
   - **Accuracy:** 97.07%
   - **Classification Report:**
     
     High precision and recall across categories.

2. **Multi-Layer Perceptron (MLP Classifier - Neural Network)**
   
   - **Accuracy:** 79.24%
   - **Comparison:**
     
     SVM outperformed MLP in accuracy.
