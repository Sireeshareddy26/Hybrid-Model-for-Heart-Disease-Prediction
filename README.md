# 🔥 Hybrid Model for Heart Disease Prediction  

## 📌 Project Overview  
This project applies **Machine Learning and Deep Learning techniques** to predict **heart disease** based on **clinical and demographic features**. The approach integrates **Decision Trees, Random Forest, SVM, Naïve Bayes, AdaBoost, Gradient Boosting, Neural Networks, LSTMs, and CNNs** to develop a **hybrid model** that significantly improves prediction accuracy.  

Using **data preprocessing, feature selection, and model partitioning**, we optimize the performance of different classifiers and validate the effectiveness of a **hybrid ensemble learning model** in comparison to individual ML algorithms.  

## 📊 Dataset  
- **Name:** Heart Disease Dataset  
- **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/45/heart+disease)  
- **Instances:** 303 (rows)  
- **Features:** 13 (columns)  

## 🚀 Methodology  
### **1️⃣ Data Preprocessing**  
- **Outlier Removal**: Boxplots are used to detect and eliminate outliers.  
- **Feature Engineering**: Data transformation and encoding of categorical values.  
- **Dataset Partitioning**: The Decision Tree model splits data into partitions (P1, P2, ..., P8) for specialized training.  

### **2️⃣ Machine Learning Models Implemented**  
✅ **Decision Tree (Entropy & Information Gain)** 🌲  
✅ **Random Forest** 🌳  
✅ **Support Vector Machine (SVM)** 📊  
✅ **Naïve Bayes** 🤖  
✅ **AdaBoost** 🔥  
✅ **Gradient Boosting** 🚀  
✅ **Linear Model (Logistic Regression)** 🏹  
✅ **Neural Network (MLPClassifier)** 🧠  
✅ **Long Short-Term Memory (LSTM)** ⏳  
✅ **Convolutional Neural Networks (CNN)** 🎯  

### **3️⃣ Hybrid Model Construction**  
- The dataset is divided into **leaf node partitions** using a **Decision Tree**.  
- Each partition is trained using different models.  
- A **hybrid model** aggregates predictions across partitions, outperforming traditional models.  

## 📈 Experimental Results  
| Model                 | Accuracy (%) |
|----------------------|------------|
| **Decision Tree**    | 84.61      |
| **Random Forest**    | 100.0      |
| **SVM**             | 61.53      |
| **Naïve Bayes**     | 84.61      |
| **AdaBoost**        | 92.30      |
| **Gradient Boost**  | 84.61      |
| **Neural Network**  | 100.0      |
| **LSTM**            | 61.53      |
| **CNN**             | 61.53      |

🚀 **Hybrid Model Accuracy**: **100%**  
🔍 **Improvement over Best Individual Model (Random Forest)**: **+24.44%**  

## 📂 Installation & Setup  
### **1️⃣ Clone the Repository**  
```sh
git clone https://github.com/your-repo-url/hybrid-heart-disease.git
cd hybrid-heart-disease
