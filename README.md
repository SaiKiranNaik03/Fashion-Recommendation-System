# Fashion Recommendation System

## 🚀 Overview
The Fashion Recommendation System is a machine learning-based application that suggests fashion items to users based on image similarity. The system leverages deep learning techniques to extract features from images and provides recommendations based on those features.

## 🔥 Features  
- Recommends visually similar fashion products based on input images.  
- Utilizes **CNN ResNet-50** for feature extraction.  
- Implements **K-Nearest Neighbors (KNN)** for finding similar products.  
- Processes a dataset of **44,000+ fashion product images**.  
- Uses **Pickle** to store trained model data for efficient retrieval.  

## 🛠️ Tech Stack  
- **Python**  
- **TensorFlow/Keras** (ResNet-50 for feature extraction)  
- **Scikit-learn** (KNN implementation)  
- **Streamlit** (for building a user-friendly interface)  
- **Pickle** (for storing trained features and model)  

## 📂 Project Structure 
![image](https://github.com/user-attachments/assets/7959dc93-1282-4075-9130-87971a28b38a)


## 🚀 How to Run  
1. Clone the repository:  
   ```bash
   git clone https://github.com/SaiKiranNaik03/Fashion-Recommendation-System
   cd fashion-recommendation
   ```
2. Install dependencies:
    ```bash
   pip install -r requirements.txt
    ```
3. Run the application:
    ```bash
   streamlit run app.py
    ```

## 📊 Dataset
- The dataset contains 44,000+ fashion product images, sourced from Myntra.
- Images are processed and feature vectors are extracted using ResNet-50.

## 📌 Working
- User uploads an image of a fashion product.
- The system extracts deep learning features using ResNet-50.
- KNN compares feature vectors and finds the most similar products.
- The system displays visually similar recommendations.

## ⚡ Future Enhancements
- Integrate real-time fashion trend analysis.
- Improve recommendation accuracy using hybrid models.
- Deploy as a web service with FastAPI or Flask.
